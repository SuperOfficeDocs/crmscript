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

     - Enum: 0 = Invalid 
     - Enum: 1 = PreChatForm 
     - Enum: 2 = Faq 
     - Enum: 3 = OfflineForm 
     - Enum: 4 = InQueue 
     - Enum: 5 = CustomerLast 
     - Enum: 6 = UserLast 
     - Enum: 7 = Finished 
     - Enum: 8 = Deleted 
     - Enum: 9 = Closed 
     - Enum: 10 = RequestPosted 
     - Enum: 11 = ClosedFromQueue 

```crmscript
NSChatSessionEntity thing;
NSChatSessionStatus status  = thing.GetStatus();
```

