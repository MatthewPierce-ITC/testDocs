---
layout: page
title: Clipboard Polling
permalink: /clipboardpolling/
nav_order: 4
parent: Create Designations
---

### Clipboard Polling

Often, rather than being handed a clean list of designations, you may receive a copy of an outline or some other document which must be mined through to find the designations that are needed for the presentation. Regardless of the document source (Word, PDF, etc.) as long as the text can be highlighted and copied to the clipboard.  Scanned images will need to have been OCR'ed in order to be used with this feature.

Activate Clipboard Polling from the Settings menu.  Doing so will apped "CLIPBOARD POLLING ACTIVE" in the title bar of the application.j

> ![Screen Grab - Clipboard Polling Menu Item](../assets/ui_menu_settings_clipboardPollingActive.png)

Highlight and copy the text, and Clip Creator will recoginize that the contents of the clipboard has changed.  Then it will pull the designation from the clipboard, validate the range, then add to the appropriate fields. Clip Creator is very flexible when it comes to this feature. Here are a few examples of formats that Clip Creator easily converts into standard designation formatting:

> - 00042:16 - 00042:20
> - 42.16-20
> - (42:16-20)
> - 42:16-42:20
> - 42-16 - 42-20
> - 42:16 thru 42:20
> - Page 42 line 16 through page 42 line 20

After Clip Creator parses out the numbers, and the range passes validation checks, you will be prompted to Make or Cancel the clip entry generation.

> ![Screen Grab - Clipboard Polling Menu Item](../assets/clipboardPolling.gif)