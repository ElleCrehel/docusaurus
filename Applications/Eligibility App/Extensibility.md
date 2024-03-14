---
sidebar_position: 4
title: Extensibility
description: Extensibility
hide_table_of_contents: false
---

## BAdI Implementations

| Object | Name | Purpose  |    
|:---|:---|:---|
| Enhancement Spot | /FLEX/BADI_ELIGIBILITY | 
| Interface | /FLEX/IF_ELIGIBILITY | Interface for BAdI: /FLEX/BADI_ELIGIBILITY |
| Implementing Class |  |
| BAdI | /FLEX/BADI_ELIGIBILITY | Eligibility BadI |

> **Important note:**  
> If the resulting hit list matches the definition of the BAdI which means:  
> - For a BAdI defined for single use, the hit list must contain exactly one BAdI implementation class
> - For a BAdI defined for multiple use, the hit list may contain multiple or no BAdI implementation classes

### Interface for BAdI: /FLEX/BADI_ELIGIBILITY

| Method | Purpose  |    
|:---|:---|
| ADD_POSTING | |
| CHECKS_BEFORE_STATUS_CHANGE | Checks before the forecast version status is changed | 
| PROCESS_AFTER_STATUS_CHANGE | Actions after the forecast version status is changed |