﻿---
uid: crmscript_ref_NSChatWidgetSettings_SetOfflineFields
title: SetOfflineFields(NSWidgetRequiredFields offlineFields)
intellisense: NSChatWidgetSettings.SetOfflineFields
keywords: NSChatWidgetSettings, GetOfflineFields
so.topic: reference
---

Required field when creating ticket in offline mode

**Parameter:** 
 - **offlineFields** NSWidgetRequiredFields
     - Enum: 0 = None 
     - Enum: 1 = Email 
     - Enum: 2 = Name 
     - Enum: 4 = Company 
     - Enum: 8 = Phone 

```crmscript
NSChatWidgetSettings thing;
NSWidgetRequiredFields offlineFields;
thing.SetOfflineFields(offlineFields);
```

