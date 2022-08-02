---
layout: page
title: Manual Entry
permalink: /manualentry/
nav_order: 1
parent: Create Designations
---

### Manual Entry

First, select the format in which you will be saving the clips. Trial Director's Clip Creation Script (.ccs), Sanction's Clip List  (.txt), Tab Delimited or Comma  Separated Values (.csv). 

> ![Screen Grab - Format Selection](../assets/ui_menu_settings_cropped.png)

This selection is optional at this point.  At any time you can change the format selection, and Clip Creator will reformat the clips for you. No work lost, no headache.

> ![Screen Grab - Animation of Format Change](../assets/formatting_autoConversion.gif)

At this point you should enter the deposition date and the deponent's name.  This will be used in the AutoID feature and to generate the filename when the work is saved.

> ![Screen Grab - Deponent Info](../assets/depoInfo_AutoID.gif)

Selecting the Line Separator checkbox allows you to add another delimiter in the Auto ID that is generated for each clip.  This is completely optional.

> ![Screen Grab - Line Separator option](../assets/depoInfo_AutoID_lineSeparator.png)

The Lines Per Page number refers to the deposion transcript itself.  Generally this value is 25, but there are times when the court reporters may use something that differs from the standard.  Clip Creator uses this value to validate the clips as they are processed and alerting the user to potential errors.

The Descriptions checkbox enables the user to enter values for such on a clip-by-clip basis.  By clicking the Sticky checkbox, this enterd value is automatically added to each successive clip that is made.

> ![Screen Grab - Description Field](../assets/manualClipEntry_non-StickyDescription.gif)

The manual mode is designed to minimize hand movement across the keyboard. The cursor will advance from one field to the next when you hit the Enter key. You may also use the backspace key to move backwards through all of the Page/Line boxes should you need to make a correction.

If you are using the Trial Director format, you are given the additional option to append the clip to the 
previous entry for a multiple segment clip as seen here:

> ![Screen Grab -  Animation Append to Previous](../assets/manualClipEntry_appendToPrevious.gif)

With each completed entry, Clip Creator will generate the required entry in the Clips window and in the data grid at the bottom of the application. The data grid has special features for modifying the clips once they are entered into the application.  See Modifying Clips for more details.