---
sidebar_position: 4
title: Portfolios
description: Portfolios
hide_table_of_contents: false
---

Some apps require the user to be linked to a [PPM portfolio](/docs/Portfolio%20and%20Project%20Management/manual.mdx), before any data is visible in the app (the data is linked to the portfolio):

- Call Cockpit
- Item Cockpit
- Form Cockpit
- Milestone Cockpit
- My Milestones
- Project Dashboard

Navigate to the FPC app, click 'Switch Portfolio' and select the desired portfolio. Now the user is linked to the portfolio, and the portfolio data should appear in the apps.

![image.png](.\img\switchport.png)

It is also possible to switch the portfolio of a user with the program /FLEX/DEMO_SWITCH_PORTFOLIO. But tis is only possible to SWITCH the portfolio, not to select a portfolio for the first time. This must always be done in the FPC app by the user or with the funcition module /RPM/SET_USER_PORTFOLIO.

After assigning/switching the portfolio, the [/FLEX/DEMO_ITEM_USERS_LINK](../General/Authorization.md) program also must be executed to assign the calls and items in the portfolio to the user. With the /FLEX/DEMO_SWITCH_PORTFOLIO program, this is already done automatically.
