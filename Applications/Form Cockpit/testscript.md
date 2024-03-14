---
title: Test Script
description: Test Script
sidebar_position: 6
hide_table_of_contents: true
---

This [Best Practice Test Script](https://cronos.sharepoint.com/:x:/t/flexso/projects/Ef-vj8oY6GVHknAHPKhRUSwBKsq_0AXVdyTHJmMolzg2ew?e=UVer2b) can help you and your customers test the solution.

| Test # | Test Case | Test Steps | Expected Result | Actual Result | Pass/Fail | Author | Comments |
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| FCP_01 | Open app | 1. Search for the 'Form Cockpit'   app on your launchpad.      2. Open the app. | The app opens and data is   visible |  *Complete   your actual result here* |  *Indicate   wether the test passed or failed (Does the actual result match with the   expected result?)* | *State your name* | *Add additional comments if   desired* |
| FCP_02 | Correct list of forms | 1. Check if all necessary form   attributes are present      2. Check if the form information is correct to what you entered in the form   app | All forms are present in the   list with the correct information |  |  |  |  |
| FCP_03 | Creating a form | 1. Click on the '+' icon      2. Check if the Form Configurator opens | A new form opens in the Form   Configurator |  |  |  |  |
| FCP_04 | Editing a form | 1. Select a form      2. Click on the pencil icon      OR      1. Click on a form      2. Click 'Edit form' | The form opens in the Form   Configuratior |  |  |  |  |
| FCP_05 | Copying a form | 1. Select a form      2. Click on the paper sheets icon | The duplicated form is now   visible in the list |  |  |  |  |
| FCP_06 | Adding   funder/program/call/phase/step/rol combinations | 1. Click on a form      2. Click the '+' icon      3. Check if the dependancy of the fields is correct (funder --> program   --> call --> phase --> step)      3. Complete the fields      4. Click 'Save' | The combinations are linked to   the form |  |  |  |  |
| FCP_07 | Negative test: do not complete   funder, program and call combination | 1. Save a combination when   leaving funder and/or program and/or call field empty      2. Check if an error message appears upon saving | It should not be possible to   create combinations without completing funder, program or call |  |  |  |  |
| FCP_08 | Negative test: add the same   parameter combination to multiple forms | 1. Save a combination on a   form      2. Save this same combination on a different form       3. Check if an error message appears upon saving | It should not be possible to add   the same parameter combination to multiple forms |  |  |  |  |
| FCP_09 | Filter forms | 1. Check if all required filters   are present      2. Check if all filters have the correct label      3. Check if all filters have the correct search helps      4. Check if the filters can be adapted (click 'Adapt filters')      4. Use the filters and check if the correct forms appear in the list (fill   out value and click 'Go') | Possible to filter on all fields   required by the user |  |  |  |  |
| FCP_10 | Export forms to excel | 1. Click 'Export' or 'Export   as…'      2. Open the excel | Excel file with a list of all   forms |  |  |  |  |
| FCP_11 | Table lay out | 1. Click 'Settings'      2. Adjust the table lay out by adding or removing columns and changing   around the order      3. Click 'Ok' | The table lay out has changed to   the configured lay out |  |  |  |  |
| FCP_12 | Variant management | 1. Create a variant (set   filters, sorting, groups, columns)      2. Click on 'Standard' or another variant that is active      3. Click 'Save As'      4. Provide a name for the variant      5. Optional: make this the default variant by selecting 'Set as Default' or   run all filtering, sorting,... automatically by selecting 'Apply   Automatically'      6. Click 'Save'      7. Open the variant to check if it was correctly saved | The variant should open as it   was configured |  |  |  |  |
| FCP_13 | Tile | 1. Check if the tile displays   the right KPI | The tile displays the right KPI |  |  |  |  |
| FCP_NF | Non-functional requirements | 1. When I open the forms   cockpit, the overview of all forms is loaded within an acceptable   timeframe      2. When I click on a form, it is opened within an accetable timeframe      2. When I copy/delete a form, it is copied/deleted within an acceptable   timeframe |  |  |  |  |  |