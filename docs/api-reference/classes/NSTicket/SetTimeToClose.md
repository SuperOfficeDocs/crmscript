---
uid: crmscript_ref_NSTicket_SetTimeToClose
title: SetTimeToClose(Integer timeToClose)
intellisense: NSTicket.SetTimeToClose
keywords: NSTicket, GetTimeToClose
so.topic: reference
---

# SetTimeToClose(Integer timeToClose)

The time (minutes) between when the ticket was created and when it was closed. Calculated based on priority&apos;s timeframe.

**Parameter:** 
 - **timeToClose** Integer

```crmscript
NSTicket thing;
Integer timeToClose;
thing.SetTimeToClose(timeToClose);
```

