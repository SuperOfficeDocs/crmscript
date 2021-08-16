---
uid: crmscript_ref_NSContactActivity_SetAction
title: SetAction(Integer action)
intellisense: NSContactActivity.SetAction
keywords: NSContactActivity, GetAction
so.topic: reference
---

# SetAction(Integer action)

The activity that has occured on this contact.

**Parameter:** 
 - **action** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = Created 
     - Enum: 2 = Updated 
     - Enum: 4 = NewActivity 
     - Enum: 8 = ActivityCompleted 
     - Enum: 16 = PersonAdded 
     - Enum: 32 = PersonUpdated 
     - Enum: 64 = DocumentAdded 
     - Enum: 127 = All 

```crmscript
NSContactActivity thing;
Integer action;
thing.SetAction(action);
```

