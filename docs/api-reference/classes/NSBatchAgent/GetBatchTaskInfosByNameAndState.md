﻿---
uid: crmscript_ref_NSBatchAgent_GetBatchTaskInfosByNameAndState
title: NSBatchTaskInfo[] GetBatchTaskInfosByNameAndState(String name, Integer state)
intellisense: NSBatchAgent.GetBatchTaskInfosByNameAndState
keywords: NSBatchAgent, GetBatchTaskInfosByNameAndState
so.topic: reference
---

Gets an array of NSBatchTaskInfo with state defined by a BatchTaskState and the batchtask definition name.

**Parameters:**
 - **name** Batchtask definition name.
 - **state** The BatchTaskState to get batch tasks for.
     - Enum: 0 = Unknown 
     - Enum: 1 = New 
     - Enum: 2 = Aquired 
     - Enum: 3 = Started 
     - Enum: 4 = Succeeded 
     - Enum: 5 = Failed 
     - Enum: 6 = SucceededManualCleanup 
     - Enum: 99999 = All 

**Returns:** NSBatchTaskInfo[]

```crmscript
NSBatchAgent agent;
String name;
Integer state;
NSBatchTaskInfo[] res = agent.GetBatchTaskInfosByNameAndState(name, state);
```

