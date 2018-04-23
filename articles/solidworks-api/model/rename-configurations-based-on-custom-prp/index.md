---
layout: article
toc: solidworks-api
title: Rename Configurations Based On Custom Property
description: Renames all configurations
image: sw-configuration-name.png
---

This macro renames all configurations of assembly or part into the value of the specified configuration specific custom property.

![SolidWorks Configuration Name](sw-configuration-name.png)

Run the macro and enter the name of the custom property to read the value from
Macro will traverse all configurations and rename them based on the corresponding value of the configuration specific custom property
If property doesn't exist in configuration or value is empty - configuration is not renamed

{% include_relative code-snippet.codesnippet %}