---
sidebar_position: 2
title: Configuration
description: Configuration
hide_table_of_contents: false

---

Purpose 

In this app, forms can be created which are used in the item (application/award/project) app. The forms are created for a combination of parameters (funder, program, call, decision point, status, role). In the form is defined 

Which information is displayed 

Which information is editable 

Which information is mandatory before going to the next status 

How the information is shown and structured 

Prerequisites 

Form parameters 

The form parameters should exist. For the funder, program and call, make sure /RPM/BUCKET_D-/FLEX/BUCKET_TYPE and /RPM/BUCKET_D-/FLEX/FUNDER and /RPM/BUCKET_D-/FLEX/PROGRAM are correctly filled. 

Form controls 

Attributes (form controls), that can be maintained, on application/project level need to be made available to be selectable in de forms. Because of that, those attributes are added as form controls. 

Form controls are stored in table /FLEX/CONTROLS. 

Controls can be added in two ways: 

Directly in table /FLEX/CONTROLS via SM30 or via the SPRO menu (SPRO > Flexso Research Management > Forms > Determine the properties of the UI5 fields that can be used) 

Via program /FLEX/FORM_CONTROLS 

Flag the “add property to CDS” 

Prerequisites: 

Field need to exist in /RPM/ITEM_D in order that it can be saved 

Form components 

Only the form components that are configured in /FLEX/COMPONENTS are available in the Form app. (SPRO > Flexso Research Management > Forms > The UI5 apps that are allowed to be used in the forms editor OR SM30 > /FLEX/COMPONENTS) 

The available components are: 

Upload component (com.flexso.frmp.component.upload) 

Long text component (com.flexso.frmp.component.longtextmaintainer) 

Referee component (com.flexso.frmp.component.refereemaintainer) 
