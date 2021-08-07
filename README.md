# Pocket for Alfred 

My fork of [fniephaus/alfred-pocket](https://github.com/fniephaus/alfred-pocket) with some tweaks for my preferences:

- Don't set a UID for the list filter; show items in the order they were saved, latest first
- Only show the URL in the subtitle, no other data

---

This workflow lets you manage your Pocket list with Alfred.

![Pocket for Alfred Screenshot](https://raw.github.com/fniephaus/alfred-pocket/master/screenshot.gif)


## Features

- Actions to copy, visit and archive, archive and delete links from your Pocket list (```fn```, ```ctrl```, ```alt``` and ```cmd```)
- Action to open link on getpocket.com (```shift```)
- Hotkey to add new links from Chrome, Safari or your clipboard with custom tags (```ctrl + L```)
- Easy to set up
- Magic argument to deauthorize the workflow (```wf:deauth```)
- Background cache refresh
- Supports notifications
- Uses OAuth 2.0 to authorize the workflow
- Saves your access_token securely in OS X's keychain


## Credits

This workflow uses [pocket](https://github.com/tapanpandita/pocket) and [alfred-workflow](https://github.com/deanishe/alfred-workflow).
