---
uid: crmscript_ref_NSChatWidgetSettings_SetOfflineFields
title: SetOfflineFields(NSWidgetRequiredFields offlineFields)
intellisense: NSChatWidgetSettings.SetOfflineFields
keywords: NSChatWidgetSettings, GetOfflineFields
so.topic: reference
---

# SetOfflineFields(NSWidgetRequiredFields offlineFields)

Required field when creating a ticket in offline mode

## Parameters

* **offlineFields** NSWidgetRequiredFields

### Enum: NSWidgetRequiredFields

* 0 = None
* 1 = Email
* 2 = Name
* 4 = Company
* 8 = Phone

## Example

```crmscript
NSChatWidgetSettings thing;
NSWidgetRequiredFields offlineFields;
thing.SetOfflineFields(offlineFields);
```
