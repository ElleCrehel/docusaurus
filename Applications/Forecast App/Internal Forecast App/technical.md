---
title: Technical Documentation
description: Internal Forecast technical documentation
tags: [Internal, Forecast]
hide_table_of_contents: false
---

## General

In the internal forecast app, integration with SAP PPM streamlines project management tasks by seamlessly synchronizing data with corresponding RPM tables, ensuring accuracy and consistency across platforms. All project-related actions, including team member management, work package creation, and accessing financial data, are conducted within SAP PPM, leveraging its comprehensive functionality for efficient project oversight and decision-making.

A crucial **parameter** is the cut-off date, which determines historical actuals, year-to-date budget, and actuals calculations, facilitating accurate forecasting from this date onward. This cut-off date ensures that previous financial performance is appropriately considered while projecting future outcomes.

## Overview 

| Object | Name | Purpose  |    
|:---|:---|:---|
| Gateway Service | /FLEX/FRMP_FORECAST_INTERNAL | Service for Internal Forecast | 
| Table | /RPM/FIN_PLAN | xRPM 4.0 Financial Planning |
| Table | /FLEX/FORECAST_H | Forecast Header information about version and related item | 
| Table | /FLEX/FORECAST_I | Forecast Internal Items |
| Table | /FLEX/FORECAST_A | Forecast Items Amounts |
| Class | /FLEX/CL_FRMP_FORECAST_INTERN | Forecast Internal Helper | 
| Class | /FLEX/CL_FRMP_FOREC_INTERN_SH | Forecast Internal Service Handler |
| Interface | /FLEX/IF_FORECAST_VERSION | Interface for BAdI: /FLEX/BADI_FORECAST_VERSION |

## Methods

### Class /FLEX/CL_FRMP_FORECAST_INTERN
| Method | Purpose  |    
|:---|:---|
| CHANGE_STATUS_VERSION | Change the status of a version | 

In this method you will find BAdI implementation [/FLEX/BADI_FORECAST_VERSION](./Extensibility.md) to: 
- Implement checks to be done before the status is changed
- Process actions after the status is changed






