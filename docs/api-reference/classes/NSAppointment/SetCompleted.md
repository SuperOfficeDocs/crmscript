---
uid: crmscript_ref_NSAppointment_SetCompleted
title: SetCompleted(Integer completed)
intellisense: NSAppointment.SetCompleted
keywords: NSAppointment, GetCompleted
so.topic: reference
---

# SetCompleted(Integer completed)

The Completed state. 

**Parameter:** 
 - **completed** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = NotStarted 
     - Enum: 2 = Started 
     - Enum: 3 = Completed 

```crmscript
NSAppointment thing;
Integer completed;
thing.SetCompleted(completed);
```

