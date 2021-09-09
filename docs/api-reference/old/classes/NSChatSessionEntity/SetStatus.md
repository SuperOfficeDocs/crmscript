---
uid: crmscript_ref_NSChatSessionEntity_SetStatus
title: SetStatus(NSChatSessionStatus status)
intellisense: NSChatSessionEntity.SetStatus
keywords: NSChatSessionEntity, GetStatus
so.topic: reference
---

# SetStatus(NSChatSessionStatus status)

Enum indicating the status for the session (pending, active, closed, etc).

## Parameters

* **status** NSChatSessionStatus

### Enum: ChatSessionStatus

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
NSChatSessionStatus status;
thing.SetStatus(status);
```
