---
title: Working with Spreadsheets
layout: page-narrow
permalink: /project/spreadsheets.html
---

# Working with Spreadsheets

We will be creating our metadata in a spreadsheet on Google Sheets, a web based spreadsheet application for editing tabular data--other common spreadsheet programs include Excel, [LibreOffice Calc](https://www.libreoffice.org/), or Mac Numbers.
Spreadsheets are a fundamental tool for working with and looking at data, so it is important to gain some basic skills.
Most spreadsheet applications follow the same basic conventions of use--this page describes details from Sheets, but the tips apply to most spreadsheet programs.

## Metadata Spreadsheet Terminology

{% include feature/image.html objectid="/assets/img/metadata_spreadsheet_parts.svg" alt="spreadsheet interface with parts labeled, including header, row, column, cell, and active cell" %}

When creating metadata in a spreadsheet we tend to use this terminology for the parts of the table:

- *columns* => "fields" (the metadata template elements used to describe specific qualities of all objects, essentially the categories of descriptions)
- *rows* => "records" or "items" (each row represents one object's description)
- *cells* => "values" (the individual chunks of metadata)

## Basics

The current cell (or active cell) is highlighted by a border of blue.
Arrow keys are used to navigate between cells (remember that the arrow keys won't be used for navigating in the text values inside the cell!).
The text bar at the top of the sheet displays the active cell's value and is used to edit the value.

Clicking "Tab" will move you to the next cell.
Clicking "Enter" will drop you to the next row down.
Clicking "Delete" key to remove the value of current cell.

To select multiple cells, hold "Ctrl" while you click on each cell you want to select. 
Holding "Shift" and clicking on a cell will select all cells in a block between the originally highlighted cell and the clicked cell.

## Drag to Fill Cells (Quick Set Up!)

You might want to set up the rows of your template first by filling in the values for the first two columns.

In the first row below your header (i.e. row 2 of the spreadsheet), in "record_contributor" enter your name. 
Now in hover your mouse over that cell, moving it to the lower right corner where you see a blue square until your mouse pointer turns into a plus sign.
Push and hold your left mouse button, and drag straight down the column over about 10 rows, then release. 
Your name value will fill in all the selected rows. 

Next, in "objectid" enter `dcm-` then your initials then `01` (e.g. `dcm-ep01`).
Hover over the cell, and follow the same click and drag as you did with your name to fill down the column.
When you release, the values will fill in with the number automatically counting upward.

This will provide you a starting point to keep your rows orderly with unique objectid's already set up!
And you can use the drag fill to quickly fill out other columns where the value repeats.

## Copy & Paste on the Web

You can not use right click to copy or paste on Google Sheets. 
Instead, you can use the standard keyboard short cuts:

- Copy: "Ctrl + C"
- Paste: "Ctrl + V"
- Undo: "Ctrl + Z"

These short cuts are handy to remember because you can use them anywhere on your computer (not just Sheets!).

Sometimes when you paste from a web page into a spreadsheet, you will end up with unexpected formatting from the web page showing up in the cell. 
On Sheets, just after you paste in a value, a clipboard icon will appear to the lower right of the cell. 
Click on the clipboard and select "Paste values only" to clean it up.

Alternatively, open Notepad or TextEdit on your computer--paste into the text editor, then copy the results in the text file, and paste into the spreadsheet--this will remove html formatting and give you a chance to clean up the text before adding to the Sheet.

Don't paste into MS Word! Word tries to preserve HTML formatting and introduces new formatting that will mess up your table.
