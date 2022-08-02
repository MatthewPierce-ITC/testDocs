---
layout: page
title: Text File Import
permalink: /import/
nav_order: 2
parent: Create Designations
---

### Import Text Files

Importing is a very fast and easy method to get your clips into the proper format. As long as you have a text file containing the clips, with a single designation on each line Clip Creator will format and error check all entries.

![Screen Grab - Manual Import Menu Item](../assets/ui_menu_settings_cropped.png)

Make sure that the file you are importing is a plain text file and that each line contains only one designation. A good rule of thumb is that if it is not readable Notepad, it won't work in Clip Creator. Like the [Clipboard Polling](create_designations_clipboard.markdown) feature, Clip Creator is very flexible when it comes to citations. For example, a file containing the following will process without errors:
```
06:05-06:07
8:11-8;15
8-21-10-06
Page 10:07-09
10:12.14
Page 10 Line 15 - Page 10 Line 18
10 22 13 06
13 07 15
15:16
```
A cleaner import file often helps resolve problems before they begin. The example on the next page shows a short import list and the resulting clips in Clip Creator using the Trial Director format.

If you are using Trial Director, clips that do not have a blank line in-between will be considered multi-segments and imported accordingly. You may easily modify the groupings once they are in Clip Creator with the Rebuild feature.

Import File Contents:
```
06:05-06:07
08:11-08:15
08:21-10:06
10:07-10:09
10:12-10:14
10:15-10:18
10:22-13:06
13:07-15:15
15:16-16:14
16:15-18:02
19:02-20:15
22:18-25:12
29:12-30:09
```
![Screen Grab Clip Creator Import File Processed](../assets/import_complete.png)