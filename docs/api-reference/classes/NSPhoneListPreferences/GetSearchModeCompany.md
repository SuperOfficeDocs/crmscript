---
uid: crmscript_ref_NSPhoneListPreferences_GetSearchModeCompany
title: Integer GetSearchModeCompany()
intellisense: NSPhoneListPreferences.GetSearchModeCompany
keywords: NSPhoneListPreferences, GetSearchModeCompany
so.topic: reference
---

# Integer GetSearchModeCompany()

The Company name search type, e.g. BeginsWith, Contains, Endswith, Matches

**Returns:** Integer

     - Enum: 0 = Exact 
     - Enum: 1 = BeginsWith 
     - Enum: 2 = EndsWith 
     - Enum: 3 = Contains 

```crmscript
NSPhoneListPreferences thing;
Integer searchModeCompany  = thing.GetSearchModeCompany();
```

