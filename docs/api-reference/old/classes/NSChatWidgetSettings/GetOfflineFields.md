---
uid: crmscript_ref_NSChatWidgetSettings_GetOfflineFields
title: NSWidgetRequiredFields GetOfflineFields()
intellisense: NSChatWidgetSettings.GetOfflineFields
keywords: NSChatWidgetSettings, GetOfflineFields
so.topic: reference
---

# NSWidgetRequiredFields GetOfflineFields()

Required field when creating ticket in offline mode

**Returns:** NSWidgetRequiredFields

## Enum: NSWidgetRequiredFields

* 0 = None
* 1 = Email
* 2 = Name
* 4 = Company
* 8 = Phone

## Example

```crmscript
NSChatWidgetSettings thing;
NSWidgetRequiredFields offlineFields  = thing.GetOfflineFields();
```
