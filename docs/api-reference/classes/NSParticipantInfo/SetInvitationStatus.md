---
uid: crmscript_ref_NSParticipantInfo_SetInvitationStatus
title: SetInvitationStatus(Integer invitationStatus)
intellisense: NSParticipantInfo.SetInvitationStatus
keywords: NSParticipantInfo, GetInvitationStatus
so.topic: reference
---

# SetInvitationStatus(Integer invitationStatus)

The participant status for the appointment

## Parameters

* **invitationStatus** Integer

### Enum: InvitationStatus

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
NSParticipantInfo thing;
Integer invitationStatus;
thing.SetInvitationStatus(invitationStatus);
```
