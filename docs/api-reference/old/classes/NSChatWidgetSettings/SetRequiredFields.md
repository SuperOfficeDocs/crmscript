---
uid: crmscript_ref_NSChatWidgetSettings_SetRequiredFields
title: SetRequiredFields(NSWidgetRequiredFields requiredFields)
intellisense: NSChatWidgetSettings.SetRequiredFields
keywords: NSChatWidgetSettings, GetRequiredFields
so.topic: reference
---

# SetRequiredFields(NSWidgetRequiredFields requiredFields)

Fields required to start a chat

## Parameters

* **requiredFields** NSWidgetRequiredFields

### Enum: NSWidgetRequiredFields

* 0 = None
* 1 = Email
* 2 = Name
* 4 = Company
* 8 = Phone

## Example

```crmscript
NSChatWidgetSettings thing;
NSWidgetRequiredFields requiredFields;
thing.SetRequiredFields(requiredFields);
```
