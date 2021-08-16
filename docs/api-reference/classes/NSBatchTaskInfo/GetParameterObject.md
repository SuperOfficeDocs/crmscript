---
uid: crmscript_ref_NSBatchTaskInfo_GetParameterObject
title: StringDictionary GetParameterObject()
intellisense: NSBatchTaskInfo.GetParameterObject
keywords: NSBatchTaskInfo, GetParameterObject
so.topic: reference
---

# StringDictionary GetParameterObject()

ParameterObject will be serialized to a binary blob and saved in the BinaryObject table. The link to the BinaryObject will be set using DetailsTable and DetailsRecord.

**Returns:** StringDictionary

```crmscript
NSBatchTaskInfo thing;
StringDictionary parameterObject  = thing.GetParameterObject();
```

