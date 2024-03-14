---
sidebar_position: 5
title: Authorization
description: Authorization
hide_table_of_contents: false
---

The /FLEX/USER_LINK table links a user, and their role, to PPM buckets (calls) and items (provides them authorization to see the items and corresponding information in the apps). 

At the customer, this table should be filled based on customer-specific logic. A program should be developed and run every time a new item (application) is created, taking care of authorizations.

Note: currently, a user can only be linked to a call or item with ONE role. 

To support implementation teams, we created a program to temporary assign authorizations, until the customer specific program is developed. The program /FLEX/DEMO_ITEM_USERS_LINK. A prerequisite is that a [portfolio must be linked](../General/Portfolios.md) to the user you want to run the program for.