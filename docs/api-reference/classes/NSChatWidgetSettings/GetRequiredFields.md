---
uid: crmscript_ref_NSChatWidgetSettings_GetRequiredFields
title: NSWidgetRequiredFields GetRequiredFields()
intellisense: NSChatWidgetSettings.GetRequiredFields
keywords: NSChatWidgetSettings, GetRequiredFields
so.topic: reference
---

# NSWidgetRequiredFields GetRequiredFields()

Fields required to start a chat

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
NSWidgetRequiredFields requiredFields  = thing.GetRequiredFields();
```
