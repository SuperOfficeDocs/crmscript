---
uid: crmscript_ref_NSAlarmData_GetInvitationStatus
title: Integer GetInvitationStatus()
intellisense: NSAlarmData.GetInvitationStatus
keywords: NSAlarmData, GetInvitationStatus
so.topic: reference
---

# Integer GetInvitationStatus()

Status if this appointment represents an invitation

**Returns:** Integer

## Enum: InvitationStatus

* 0 = Unknown
* 1 = None
* 2 = Accepted
* 4 = Hidden
* 5 = Invitation
* 6 = Moved
* 7 = Seen
* 8 = MovedSeen
* 9 = Declined
* 10 = Cancelled

## Example

```crmscript
NSAlarmData thing;
Integer invitationStatus  = thing.GetInvitationStatus();
```
