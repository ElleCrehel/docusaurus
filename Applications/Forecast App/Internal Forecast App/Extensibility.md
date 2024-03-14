---
sidebar_position: 4
title: Extensibility
description: Extensibility
hide_table_of_contents: false
---

## BAdI Implementations

| Object | Name | Purpose  |    
|:---|:---|:---|
| Enhancement Spot | /FLEX/BADI_FORECAST_VERSION | 
| Interface | /FLEX/IF_FORECAST_VERSION | Interface for BAdI: /FLEX/BADI_FORECAST_VERSION |
| Implementing Class | ZCL_BADI_FORECAST |
| BAdI | /FLEX/BADI_FORECAST_VERSION | Forecast Version BadI |

> **Important note:**  
> If the resulting hit list matches the definition of the BAdI which means:  
> - For a BAdI defined for single use, the hit list must contain exactly one BAdI implementation class
> - For a BAdI defined for multiple use, the hit list may contain multiple or no BAdI implementation classes

### Interface for BAdI: /FLEX/BADI_FORECAST_VERSION

| Method | Purpose  |    
|:---|:---|
| CHECKS_BEFORE_STATUS_CHANGE | Checks before the forecast version status is changed | 
| PROCESS_AFTER_STATUS_CHANGE | Actions after the forecast version status is changed |