# Privacy Policy — snippetFlow

_Last updated: 3 October 2026_

Published by auralFlow.

snippetFlow turns short typed shortcuts into longer text. It is built to keep your data on your own computer. The one exception is sync, which is off unless you switch it on (see below).

## What it stores

- **Your snippets and settings** (shortcuts, snippet text, folders, tags, date format, paused sites) and **usage counts** (how often and when each snippet was last used).
- All of this is saved with `chrome.storage.local` in your browser profile. It is never sent to us or anyone else.
- **Images and attachments** you add to snippets are kept in the extension's own storage on your computer (IndexedDB). They are put into an email only when you expand a snippet that uses them, and they are never synced.
- A fresh install starts with a few **example snippets** (in an "Examples" folder) so you can see how shortcuts work. They are generic text written for this extension, contain no real names or addresses, and can be edited or deleted like any other snippet.

## Sync (optional, off by default)

If you switch on **Sync snippets with this Chrome profile** in Settings, the text of your snippets, your folders and your date format are also saved with `chrome.storage.sync`. Chrome then copies them, through your own Google account, to the other computers where you are signed in to Chrome with sync on. That data is handled by Google under your Chrome sync settings; it is not sent to us.

- Not synced: usage counts, pause, disabled sites, images and attachments.
- Switching sync off stops the copying and deletes nothing.

## What it reads, and when

- **What you type in text boxes**, so it can spot a shortcut such as `!please`. Only the text just before the cursor is checked, in your browser, and it is not saved or sent anywhere.
- **Your clipboard**, only when you expand a snippet that contains `{clipboard}`, to paste its contents into that snippet. The read happens in a hidden extension page that is closed again straight after, so the text is not kept.
- **In Gmail, the first "To" recipient's name and the subject line** of the draft you are writing, only when a snippet uses `{name}` or `{subject}`.
- **The address of the current tab**, only when you click the toolbar button (the `activeTab` permission), so the popup can turn the extension off for that site. The extension has no standing access to page addresses.

## What it does not do

- It makes no network requests of its own. There are no servers of ours, no accounts with us, no analytics, ads or tracking. (With sync switched on, Chrome itself carries the synced data.)
- It does not sell, share or transfer your data to anyone.
- It does not use your data for anything except expanding your snippets.

## Removing your data

Delete snippets from the settings page, or uninstall the extension, which removes everything it stored.

## Contact

Questions: AaronDuncan300@gmail.com
