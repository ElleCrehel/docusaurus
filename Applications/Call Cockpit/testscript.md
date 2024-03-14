---
title: Test Script
description: Test Script for Call Cockpit
sidebar_position: 6
hide_table_of_contents: true

---

This [Best Practice Test Script](https://cronos.sharepoint.com/:x:/t/flexso/projects/Ef-vj8oY6GVHknAHPKhRUSwBKsq_0AXVdyTHJmMolzg2ew?e=UVer2b) can help you and your customers test the solution.

| Test # | Test Case | Test Steps | Expected Result | Actual Result | Pass/Fail | Author | Comments |
|---|---|---|---|---|---|---|---|
| CCP_01 | Open app | 1. Search for the 'Call Cockpit' app on your launchpad.<br />2. Open the app. | The app opens and data is   visible |  *Complete your actual result here*|  *Indicate wether the test passed or failed (Does the actual result match with the expected result?)*|  *State your name*| *Add additional comments if desired* |
| CCP_02 | Correct list of calls | 1. Check if all necessary call attributes are present<br />2. Check if all calls you are authorized to view are present<br />3. Check if the call information is correct to what you entered in the FPC app | All calls you are authorized to   are present in the list with the correct information |  |  |  |  |
| CCP_03 | Creating an application | 1. Click on a call <br />  2. Check if the form you have created for this form combination opens | The right form should open based   on the form combination |  |  |  |  |
| CCP_04 | Negative test: starting an   application for a call with no form combination | 1. Check that it is impossible to create an application for a call with no form combination | If no form combination for the   call exists, it should not be possible to start an application for this call |  |  |  |  |
|  | Negative test: starting an   application for an inactive call (custom code) | 1. Check that it is impossible to create an application for an inactive call (based on the custom code of your organisation | It should not be possible to   create an application for an inactive call |  |  |  |  |
| CCP_05 | Filter calls | 1. Check if all required filters are present  <br />2. Check if all filters have the correct label <br />  3. Check if all filters have the correct search helps   <br />4. Check if the filters can be adapted (click 'Adapt filters')  <br /> 5. Use the filters and check if the correct calls appear in the list (fill   out value and click 'Go') | Possible to filter on all fields   required by the user |  |  |  |  |
| CCP_06 | Export calls to excel | 1. Click 'Export' or 'Export as…' <br />  2. Open the excel | Excel file with a list of all   calls |  |  |  |  |
| CCP_07 | Table lay out | 1. Click 'Settings'  <br /> 2. Adjust the table lay out by adding or removing columns and changing around the order  <br /> 3. Click 'Ok' | The table lay out has changed to   the configured lay out |  |  |  |  |
| CCP_08 | Variant management | 1. Create a variant (set filters, sorting, groups, columns)<br />   2. Click on 'Standard' or another variant that is active  <br /> 3. Click 'Save As'  <br /> 4. Provide a name for the variant <br />  5. Optional: make this the default variant by selecting 'Set as Default' or run all filtering, sorting,... automatically by selecting 'Apply Automatically'  <br /> 6. Click 'Save' <br />  7. Open the variant to check if it was correctly saved | The variant should open as it   was configured |  |  |  |  |
| CCP_09 | Tile | 1. Check if the tile displays the right KPI | The tile displays the right KPI |  |  |  |  |
| CCP_NF | Non-functional requirements | 1. When I open the call cockpit, the overview of all calls is loaded within an acceptable timeframe  <br /> 2. When I click on a call, it is opened within an accetable timeframe <br />  3. When stress tested (simulation of x users), the app performs well |  |  |  |  |  |