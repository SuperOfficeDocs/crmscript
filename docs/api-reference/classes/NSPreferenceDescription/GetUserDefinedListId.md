---
uid: crmscript_ref_NSPreferenceDescription_GetUserDefinedListId
title: Integer GetUserDefinedListId()
intellisense: NSPreferenceDescription.GetUserDefinedListId
keywords: NSPreferenceDescription, GetUserDefinedListId
so.topic: reference
---

# Integer GetUserDefinedListId()

Read-only field, If valueType = 5, and TableName is UDList, then UserdefinedLIstId contains the id of the list referenced by the preference

**Returns:** Integer

```crmscript
NSPreferenceDescription thing;
Integer userDefinedListId  = thing.GetUserDefinedListId();
```

