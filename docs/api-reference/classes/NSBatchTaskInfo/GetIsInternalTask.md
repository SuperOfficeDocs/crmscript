---
uid: crmscript_ref_NSBatchTaskInfo_GetIsInternalTask
title: Bool GetIsInternalTask()
intellisense: NSBatchTaskInfo.GetIsInternalTask
keywords: NSBatchTaskInfo, GetIsInternalTask
so.topic: reference
---

# Bool GetIsInternalTask()

If IsInternalTask is true, this task will not add a trace to the database.

**Returns:** Bool

```crmscript
NSBatchTaskInfo thing;
Bool isInternalTask  = thing.GetIsInternalTask();
```

