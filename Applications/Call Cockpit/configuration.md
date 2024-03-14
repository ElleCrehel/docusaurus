---
sidebar_position: 2
title: Configuration
description: Configuration
hide_table_of_contents: false

---

As a functional consultant, you want to focus on implementation and content. Here we explain you how to get the app running, with the right actions listed for the technical team.

## Configuration

For this app, no specific configuration is required.

## Other Prerequisites

To see the existing calls in the Call Cockpit, you should be [linked to a portfolio](../General/Portfolios.md). You will only see the calls of the portolio you are linked to.

You also must be authorized to see the calls. Note that authorization is a customer specific implementation, but we provide a program /FLEX/DEMO_ITEM_USERS_LINK that allows you to manually link users to calls.

Custom logic can be implemented to make calls appear active or inactive in the Call Cockpit. For example (standard FRMP implementation, delivered with the package):

-	The publication date is in the past 
-	The submission deadline is in the future

If no calls are active, make sure to check these requirements.

If you can't start an application for the call, check if a form for the specific initial lifecycle step and status exists (Funder - Program - Call - Lifecycle step - Status, no role!).

