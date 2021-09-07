---
uid: crmscript_ref_NSChatSessionEntity_GetStatus
title: NSChatSessionStatus GetStatus()
intellisense: NSChatSessionEntity.GetStatus
keywords: NSChatSessionEntity, GetStatus
so.topic: reference
---

# NSChatSessionStatus GetStatus()

Enum indicating the status for the session (pending, active, closed, etc).

**Returns:** NSChatSessionStatus

## Enum: ChatSessionStatus

* 0 = Invalid
* 1 = PreChatForm
* 2 = Faq
* 3 = OfflineForm
* 4 = InQueue
* 5 = CustomerLast
* 6 = UserLast
* 7 = Finished
* 8 = Deleted
* 9 = Closed
* 10 = RequestPosted
* 11 = ClosedFromQueue

## Example

```crmscript
NSChatSessionEntity thing;
NSChatSessionStatus status  = thing.GetStatus();
```
