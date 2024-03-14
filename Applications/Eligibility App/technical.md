---
title: Technical Documentation
description: External Forecast technical documentation
tags: [Eligibility]
hide_table_of_contents: false
---

## General

The Eligibility app serves as a crucial tool for managing financial actuals within projects. Its primary function is to retrieve and display actual financial data booked on WBS elements. Users can interact with the data through the Eligibility Actuals view, where they can mark entries as eligible or verified, adjust category mappings, and utilize features like add posting and create line item.  

Additionally, the app offers an overview screen that provides a comprehensive breakdown of financial actuals by funder, work package, category, and budget line, facilitating detailed analysis and decision-making. Overall, the Eligibility app streamlines the process of managing project finances, ensuring accuracy and efficiency in tracking actual expenditures.

## Overview

| Object | Name | Purpose  |    
|:---|:---|:---|
| Gateway Service | /FLEX/FRMP_ELIGIBILITY | Service for Eligibility | 
| Table | /FLEX/ELIGIBIL_H | Eligibility Header information about version and related item | 
| Table | /FLEX/ELIGIBIL_I | Eligibility Items |
| Table | /FLEX/ELIGIBIL_O | Eligibility Overview |
| Class | /FLEX/CL_FRMP_ELIGIBILITY | Eligibility Helper | 
| Class | /FLEX/CL_FRMP_ELIGIBILITY_SH | Eligibility Service Handler |
| Interface | /FLEX/IF_ELIGIBILITY | Interface for BAdI: /FLEX/BADI_ELIGIBILITY |

## Methods

### Class /FLEX/CL_FRMP_ELIGIBILITY
| Method | Purpose  |    
|:---|:---|
| ADD_POSTING | Add a posting |
| CHANGE_STATUS_VERSION | Change the status of a version | 

In these methods you will find BAdI implementation [/FLEX/BADI_ELIGIBILITY](./Extensibility.md) to either:
- Add a posting
- Implement checks to be done before the status is changed
- Process actions after the status is changed
