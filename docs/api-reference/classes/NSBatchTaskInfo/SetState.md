---
uid: crmscript_ref_NSBatchTaskInfo_SetState
title: SetState(Integer state)
intellisense: NSBatchTaskInfo.SetState
keywords: NSBatchTaskInfo, GetState
so.topic: reference
---

# SetState(Integer state)

BatchTaskState of the task.

**Parameter:** 
 - **state** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = New 
     - Enum: 2 = Aquired 
     - Enum: 3 = Started 
     - Enum: 4 = Succeeded 
     - Enum: 5 = Failed 
     - Enum: 6 = SucceededManualCleanup 
     - Enum: 99999 = All 

```crmscript
NSBatchTaskInfo thing;
Integer state;
thing.SetState(state);
```

