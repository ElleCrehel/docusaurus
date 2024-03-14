---
title: Test Script
description: Test Script
sidebar_position: 6
hide_table_of_contents: false

---

This [Best Practice Test Script](https://cronos.sharepoint.com/:x:/t/flexso/projects/Ef-vj8oY6GVHknAHPKhRUSwBKsq_0AXVdyTHJmMolzg2ew?e=UVer2b) can help you and your customers test the solution.

| Test # | Test Case | Test Steps | Expected Result | Actual Result | Pass/Fail | Author | Comments |
|---|---|---|---|---|---|---|---|
| MST_01 | Open app | 1. Open the application, award   or project cockpit.      2. Select an item. A popup, with applications to which you can navigate,   opens.      3. Click on "maintain milestone(s)".      4. The app opens and the header shows the correct item information. In case   some milestones are created automatically or milestones have been created   before, they are listed in the overview. | The app opens and data is   visible and correct. |  *Complete   your actual result here* |  *Indicate   wether the test passed or failed (Does the actual result match with the   expected result?)* | *State your name* | *Add additional comments if   desired* |
| MST_02 | Create milestone(s) | 1. Click '+'.      2. Complete the milestone attributes.      3. Select between a fixed or variable due date (Fixed due date: select a   planned date; variable due date: select a project date and an amount of day   to add to project date)      4. Click 'Save' | The correct milestone types are   shown.      The newly created milestone(s) should appear in the list, with correct   values. |  |  |  |  |
| MST_03 | Edit milestone(s) | 1. Edit an already existing   milestone.      2. Click 'Save'   | Completed milestones are greyed   out and cannot be edited anymore.      The changes on other milestones should be saved. |  |  |  |  |
| MST_04 | Delete milestone(s) | 1. Select one or multiple   milestone(s)      2. Click the trashcan icon      3. Click 'Save' | The deleted milestone(s) should   disappear from the list |  |  |  |  |
| MST_05 | Copy milestone(s) | 1. Select one or multiple   milestone(s)      2. Click the paper sheets icon      3. Make the necessary changes to the copied line.      4. Click 'Save' | The milestone(s) should be   duplicated in the list |  |  |  |  |
| MST_06 | Negative test: saving milestone   with empty required fields | 1. Create a milestone and leave   required fields empty      2. Check if an error message appears upon saving | It should not be possible to   save a milstone with empty required fields |  |  |  |  |
| MST_07 | Negative test: creating multiple   milestones for a milestone type for which only one milestone can exist | 1. Create multiple milestones   for a milestone type for which only one milestone can exist      2. Check if an error message appears upon saving | It should nog be possible to   create multiple milestones for a milestone type for which only one milestone   can exist. This is based on configuration of the milestone types. |  |  |  |  |
| MST_08 | Negative test: creating a   milestone with a due date in the past | 1. Create a milestone with a   planned date in the past      2. Check if a warning message appears | It should be possible to create   a milestone with a date in the past but a warning message should pop up to   inform you. |  |  |  |  |