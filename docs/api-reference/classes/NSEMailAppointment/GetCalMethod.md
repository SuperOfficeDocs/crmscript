---
uid: crmscript_ref_NSEMailAppointment_GetCalMethod
title: Integer GetCalMethod()
intellisense: NSEMailAppointment.GetCalMethod
keywords: NSEMailAppointment, GetCalMethod
so.topic: reference
---

# Integer GetCalMethod()

Method field stored in ICS file.

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = Add 
     - Enum: 2 = Cancel 
     - Enum: 3 = Counter 
     - Enum: 4 = DeclineCounter 
     - Enum: 5 = Publish 
     - Enum: 6 = Refresh 
     - Enum: 7 = Reply 
     - Enum: 8 = Request 

```crmscript
NSEMailAppointment thing;
Integer calMethod  = thing.GetCalMethod();
```

