---
uid: crmscript_ref_NSPreferenceDescription_SetValueType
title: SetValueType(Integer valueType)
intellisense: NSPreferenceDescription.SetValueType
keywords: NSPreferenceDescription, GetValueType
so.topic: reference
---

# SetValueType(Integer valueType)

1=number, 2=text, 3=bool, 4=list of values; 5=list table ref; 6=contact ID, 7=Person ID, 8=Project ID, 9=Selection ID

**Parameter:** 
 - **valueType** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = Number 
     - Enum: 2 = Text 
     - Enum: 3 = Bool 
     - Enum: 4 = ListOfValues 
     - Enum: 5 = ListTableRef 
     - Enum: 6 = TimeList 
     - Enum: 7 = ContactID 
     - Enum: 8 = PersonID 
     - Enum: 9 = ProjectID 
     - Enum: 10 = SelectionID 
     - Enum: 11 = PosSize 
     - Enum: 12 = TimeZone 
     - Enum: 13 = Time 
     - Enum: 14 = Password 
     - Enum: 15 = MultiLineText 

```crmscript
NSPreferenceDescription thing;
Integer valueType;
thing.SetValueType(valueType);
```

