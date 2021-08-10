---
uid: crmscript_ref_NSTicketCategoryEntity_SetFlags
title: SetFlags(TicketCategoryFlags flags)
intellisense: NSTicketCategoryEntity.SetFlags
keywords: NSTicketCategoryEntity, GetFlags
so.topic: reference
---

# SetFlags(TicketCategoryFlags flags)

A bitmask representing flags for this category.

**Parameter:** 
 - **flags** TicketCategoryFlags
     - Enum: 0 = Unknown 
     - Enum: 1 = Internal 
     - Enum: 2 = OnlyLoggedInUsers 
     - Enum: 4 = DefaultToCategoryMaster 
     - Enum: 8 = ListInMain 
     - Enum: 16 = RedelegateNewMsg 
     - Enum: 32 = DelegateToOurContact 
     - Enum: 64 = PropagateReplyTemplate 
     - Enum: 128 = MembersOnly 
     - Enum: 256 = NotifyMembers 
     - Enum: 512 = AcceptWhenReplying 

```crmscript
NSTicketCategoryEntity thing;
TicketCategoryFlags flags;
thing.SetFlags(flags);
```

