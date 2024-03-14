---
title: Test Script
description: Test Script
sidebar_position: 6
hide_table_of_contents: false

---

This [Best Practice Test Script](https://cronos.sharepoint.com/:x:/t/flexso/projects/Ef-vj8oY6GVHknAHPKhRUSwBKsq_0AXVdyTHJmMolzg2ew?e=UVer2b) can help you and your customers test the solution.

# Application Cockpit

| Test # | Test Case | Test Steps | Expected Result | Actual Result | Pass/Fail | Author | Comments |
|---|---|---|---|---|---|---|---|
| ACP_01 | Open app | 1. Search for the 'Application   Cockpit' app on your launchpad.      2. Open the app. | The app opens and data is   visible |  *Complete   your actual result here* |  *Indicate   wether the test passed or failed (Does the actual result match with the   expected result?)* | *State your name* | *Add additional comments if   desired* |
| ACP_02 | Correct list of applications | 1. Check if all necessary   application attributes are present      2. Check if all applications you are authorized to view are present      3. Check if the application information is correct to what you previously   entered | All applications you are   authorized to are present in the list with the correct information |  |  |  |  |
| ACP_03 | Navigating to another app | 1. Click on an application      2. Check if the required apps to navigate to appear in the list      3. Check if it is possible to navigate to each listed app      4. Check if the correct application opens in the selected app | It should be possible to   navigate to the desired app with the selected application opening   automatically |  |  |  |  |
| ACP_04 | Filter applications | 1. Check if all required filters   are present      2. Check if all filters have the correct label      3. Check if all filters have the correct search helps      4. Check if the filters can be adapted (click 'Adapt filters')      5. Use the filters and check if the correct applications appear in the list   (fill out value and click 'Go') | Possible to filter on all fields   required by the user |  |  |  |  |
| ACP_05 | Table lay out | 1. Click 'Settings'      2. Adjust the table lay out by adding or removing columns and changing   around the order      3. Click 'Ok' | The table lay out has changed to   the configured lay out |  |  |  |  |
| ACP_06 | Variant management | 1. Create a variant (set   filters, sorting, groups, columns)      2. Click on 'Standard' or another variant that is active      3. Click 'Save As'      4. Provide a name for the variant      5. Optional: make this the default variant by selecting 'Set as Default' or   run all filtering, sorting,... automatically by selecting 'Apply   Automatically'      6. Click 'Save'      7. Open the variant to check if it was correctly saved | The variant should open as it   was configured |  |  |  |  |
| ACP_07 | Tile | 1. Check if the tile displays   the right KPI | The tile displays the right KPI |  |  |  |  |
| ACP_NF | Non-functional requirements | 1. When I open the application   cockpit, the overview of all applications is loaded within an acceptable   timeframe |  |  |  |  |  |

# Award Cockpit

| Test # | Test Case | Test Steps | Expected Result | Actual Result | Pass/Fail | Author | Comments |
|---|---|---|---|---|---|---|---|
| AWA_01 | Open app | 1. Navigate to the award app   from the award cockpit | The app opens and data is   visible |  *Complete   your actual result here* |  *Indicate   wether the test passed or failed (Does the actual result match with the   expected result?)* | *State your name* | *Add additional comments if   desired* |
| AWA_02 | Opening an awarded application | see AWC_02 | An awarded application should   open with the correct information |  |  |  |  |
| AWA_03 | Complete the awarded application | 1. Click 'Edit' to go into edit   mode      2. Update the information (at least all required fields) | The awarded application is   edited |  |  |  |  |
| AWA_04 | Save the awarded application | 1. Click on 'Save'      2. Check if the new or updated information is saved      3. Click 'Save to next phase'      4. Select the next phase for the application      5. Check if the application is pushed to the project phase      6. The application should become visible in the project cockpit (and   dissapear from the application cockpit). | The awarded application should   dissapear from the award cockpit, and a new project should appear in the   project cockpit |  |  |  |  |
| AWA_05 | Negative test: saving awarded   application with empty required fields | 1. Edit the awarded application   and leave required fields empty      2. Check if an error message appears upon saving | It should not be possible to   save an awarded application with empty required fields |  |  |  |  |
| AWA_06 | Tile | 1. Check if the tile displays   the right KPI | The tile displays the right KPI |  |  |  |  |
| AWA_NF | Non-functional requirements | 1. When I open an awarded   application, it is opened within an accetable timeframe |  |  |  |  |  |

# Project Cockpit

| Test # | Test Case | Test Steps | Expected Result | Actual Result | Pass/Fail | Author | Comments |
|---|---|---|---|---|---|---|---|
| PCP_01 | Open app | 1. Search for the 'Project   Cockpit' app on your launchpad.      2. Open the app. | The app opens and data is   visible |  *Complete   your actual result here* |  *Indicate   wether the test passed or failed (Does the actual result match with the   expected result?)* | *State your name* | *Add additional comments if   desired* |
| PCP_02 | Correct list of projects | 1. Check if all necessary   project attributes are present      2. Check if all projects you are authorized to view are present      3. Check if the project information is correct to what you entered in the   award/project app | All projects you are authorized   to are present in the list with the correct information |  |  |  |  |
| PCP_03 | Navigating to another app | 1. Click on a project      2. Check if the required apps to navigate to appear in the list      3. Check if it is possible to navigate to each listed app      4. Check if the correct project opens in the selected app | It should be possible to   navigate to the desired app with the selected project opening automatically |  |  |  |  |
| PCP_04 | Filter projects | 1. Check if all required filters   are present      2. Check if all filters have the correct label      3. Check if all filters have the correct search helps      4. Check if the filters can be adapted (click 'Adapt filters')      4. Use the filters and check if the correct projects appear in the list   (fill out value and click 'Go') | Possible to filter on all fields   required by the user |  |  |  |  |
| PCP_05 | Export projects to excel | 1. Click 'Export' or 'Export   as…'      2. Open the excel | Excel file with a list of all   projects |  |  |  |  |
| PCP_06 | Table lay out | 1. Click 'Settings'      2. Adjust the table lay out by adding or removing columns and changing   around the order      3. Click 'Ok' | The table lay out has changed to   the configured lay out |  |  |  |  |
| PCP_07 | Variant management | 1. Create a variant (set   filters, sorting, groups, columns)      2. Click on 'Standard' or another variant that is active      3. Click 'Save As'      4. Provide a name for the variant      5. Optional: make this the default variant by selecting 'Set as Default' or   run all filtering, sorting,... automatically by selecting 'Apply   Automatically'      6. Click 'Save'      7. Open the variant to check if it was correctly saved | The variant should open as it   was configured |  |  |  |  |
| PCP_08 | Tile | 1. Check if the tile displays   the right KPI | The tile displays the right KPI |  |  |  |  |
| PCP_NF | Non-functional requirements | 1. When I open the project   cockpit, the overview of all projects is loaded within an acceptable   timeframe |  |  |  |  |  |