---
uid: crmscript_ref_NSAppointment_GetInvitationStatus
title: Integer GetInvitationStatus()
intellisense: NSAppointment.GetInvitationStatus
keywords: NSAppointment, GetInvitationStatus
so.topic: reference
---

# Integer GetInvitationStatus()

Status if this appointment represents an invitation

**Returns:** Integer

     - Enum: 0 = Unknown 
     - Enum: 1 = None 
     - Enum: 2 = Accepted 
     - Enum: 4 = Hidden 
     - Enum: 5 = Invitation 
     - Enum: 6 = Moved 
     - Enum: 7 = Seen 
     - Enum: 8 = MovedSeen 
     - Enum: 9 = Declined 
     - Enum: 10 = Cancelled 

```crmscript
NSAppointment thing;
Integer invitationStatus  = thing.GetInvitationStatus();
```

