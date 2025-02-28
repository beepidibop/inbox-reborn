# Inbox Reborn theme for Gmail™
#### *Formerly known as Inbox in Gmail*

Web extension which modifies Gmail™ to bring back the features and uncluttered design you knew and loved from Google's discontinued Inbox

![inbox screenshot](https://github.com/team-inbox/inbox-reborn/blob/master/screenshots/inbox%20v0.4.8-3.png?raw=true)

## Installing

### Chrome & Microsoft Edge 

The extension has been updated to version 0.5.9.26. It can be added through the following link

https://chrome.google.com/webstore/detail/inbox-reborn-theme-for-gm/bkphmihkdbdgedlaflnkhnmnmibffomf


### Firefox

[Firefox Add-ons: Inbox in Gmail](https://addons.mozilla.org/firefox/addon/inbox-in-gmail)

Install Inbox Reborn as an **unsigned Firefox addon** (sometimes the version on the Firefox add-ons site is out of date):
1. Download [this repo's source code here](https://github.com/team-inbox/inbox-reborn/archive/master.zip), and unzip it where you like
2. Create a new zip file of the main folder's content, so that there is no containing 'inbox-reborn-master' folder
3. Make sure the Firefox setting `xpinstall.signatures.required` is set to `false` - this is done in `about:config`
4. On the Firefox addons page, use the "Install Add-on From File..." on the gear menu to install the addon from the zip file you just created


## Features

- Bundle emails by label and category
- Group emails by date (today, yesterday, this month, etc)
- Clean interface to return to the simplicity of Inbox
- Display emails sent to yourself with subject "Reminder" as reminders
- Colored avatars based on senders name
- Calendar events displayed in a small card, with inline responses


## Extension Options

![options popup screenshot](https://github.com/team-inbox/inbox-reborn/blob/master/screenshots/options%20v0.4.8-2.png?raw=true)

Click the extension's icon at the top right of your browser to adjust the behavior of some features:

#### Reminders
This option is used to determine how to treat emails sent to yourself.

- All are treated as reminders. 
- Only emails with a subject containing the word "reminder" are treated as reminders. 
- Leave the emails as they are. (Disable)

#### Email Bundling
This option is used to bundle emails by label in the inbox.

- Toggle Enable/Disable

#### Email Avatars
This option will show a circle with the first letter initial of the sender, to the left of the email in your folder.
- Toggle Enable/Disable


## Recommended Gmail™ Settings

Using these settings will more closely replicate the visual style of Inbox:

- Settings/Inbox/Categories -> Leave only Primary ticked
- Settings/Inbox/Inbox Type -> Default or Starred First
- Settings/Advanced/Multiple Inbox -> Disabled
- Settings/Advanced/Preview Pane -> Disabled
- Settings/General/Maximum Page Size -> Show 100 conversations per page
- Settings/General/Personal level indicators -> No indicators
- Settings/Inbox/Importance markers -> No markers


## Email Bundling Tips

Disable inbox category tabs:
- Settings Dropdown/Configure Inbox -> Leave only Primary ticked -> Save

Allow default category labels (Promotions, Social, Updates, Forums) to be bundled:
- Settings/Labels/Categories/Show in message List -> Click show for each category

If you'd like a specific label not to be bundled, create a label called 'Unbundled', and nest that label within it.


## Known Issues

- This extension works best in English, because it relies on specific date formats.
- This currently only supports Gmail™'s default theme. If you enable the Dark theme, you will experience white/invisible text and icons.


## Privacy

- This extension does not make any external network requests.
- This extension does not use any analytics platforms.
- The code is open source, ready for you to audit.

In other words, you are not being tracked, and your data is not leaving the page to be processed or stored anywhere else. This extension just sits as a layer on top of Gmail™, modifying the style and behavior of the page.
