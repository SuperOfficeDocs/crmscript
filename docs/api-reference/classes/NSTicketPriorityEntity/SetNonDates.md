﻿---
uid: crmscript_ref_NSTicketPriorityEntity_SetNonDates
title: SetNonDates(DateTime[]nonDates)
intellisense: NSTicketPriorityEntity.SetNonDates
keywords: NSTicketPriorityEntity, GetNonDates
so.topic: reference
---

Dates which the escalation time should not be running. Note that only the day of the year (day and month) is used. So the year and time part is not used even if this is a DateTime

**Parameter:** 
 - **nonDates** DateTimeArray

```crmscript
NSTicketPriorityEntity thing;
DateTime[]nonDates;
thing.SetNonDates(nonDates);
```

