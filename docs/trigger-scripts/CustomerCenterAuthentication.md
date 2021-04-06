---
title: triggerscripts
description: Trigger scripts
so.author: Christian Mogensen
so.date: 11.11.2020
keywords:
---

# CustomerCenterAuthentication (210)

## Input values

* `username` = user string
* `targetId` = temporary key info ID (optional)

## Output

* `navigateTo` set to URL to redirect to

## Sample code

```crmscript
#setLanguageLevel 3;
String param1 = getVariable("personId");
```