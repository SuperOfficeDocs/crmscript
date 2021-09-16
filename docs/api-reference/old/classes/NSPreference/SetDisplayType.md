---
uid: crmscript_ref_NSPreference_SetDisplayType
title: SetDisplayType(Integer displayType)
intellisense: NSPreference.SetDisplayType
keywords: NSPreference, GetDisplayType
so.topic: reference
---

# SetDisplayType(Integer displayType)

Display type, populated when asked for.

## Parameters

* **displayType** Integer
* Enum: 0 = Unknown
* Enum: 1 = Number
* Enum: 2 = Text
* Enum: 3 = Bool
* Enum: 4 = ListOfValues
* Enum: 5 = ListTableRef
* Enum: 6 = TimeList
* Enum: 7 = ContactID
* Enum: 8 = PersonID
* Enum: 9 = ProjectID
* Enum: 10 = SelectionID
* Enum: 11 = PosSize
* Enum: 12 = TimeZone
* Enum: 13 = Time
* Enum: 14 = Password
* Enum: 15 = MultiLineText

```crmscript
NSPreference thing;
Integer displayType;
thing.SetDisplayType(displayType);
```
