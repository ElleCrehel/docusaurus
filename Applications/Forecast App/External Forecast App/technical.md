---
title: Technical Documentation
description: External Forecast technical documentation
tags: [External, Forecast]
hide_table_of_contents: false
---

## General

In the external forecast app, seamless interaction with custom /FLEX/ tables replicates the flexibility and functionality akin to RPM tables in the internal forecast app. All project-related activities, including team member management, work package creation, and accessing financial or budget data, are facilitated through these /FLEX/ tables, ensuring consistency and efficiency in data handling.

A crucial parameter is the **cut-off date**, which determines historical actuals, year-to-date budget, and actuals calculations, facilitating accurate forecasting from this date onward. This cut-off date ensures that previous financial performance is appropriately considered while projecting future outcomes.

## Overview

| Object | Name | Purpose  |    
|:---|:---|:---|
| Gateway Service | /FLEX/FRMP_FORECAST_EXTERNAL | Service for External Forecast | 
| Table | /FLEX/FORECAST_H | Forecast Header information about version and related item | 
| Table | /FLEX/FORECAST_E | Forecast External Items |
| Table | /FLEX/FORECAST_A | Forecast Items Amounts |
| Class | /FLEX/CL_FRMP_FORECAST_EXTERN | Forecast External Helper | 
| Class | /FLEX/CL_FRMP_FOREC_EXTERN_SH | Forecast External Service Handler |
| Interface | /FLEX/IF_FORECAST_VERSION | Interface for BAdI: /FLEX/BADI_FORECAST_VERSION |

## Methods

### Class /FLEX/CL_FRMP_FORECAST_EXTERN
| Method | Purpose  |    
|:---|:---|
| CHANGE_STATUS_VERSION | Change the status of a version | 

In this method you will find BAdI implementation [/FLEX/BADI_FORECAST_VERSION](./Extensibility.md) to: 
- Implement checks to be done before the status is changed
- Process actions after the status is changed


