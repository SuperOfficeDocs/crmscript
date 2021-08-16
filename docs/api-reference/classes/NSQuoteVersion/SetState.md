---
uid: crmscript_ref_NSQuoteVersion_SetState
title: SetState(Integer state)
intellisense: NSQuoteVersion.SetState
keywords: NSQuoteVersion, GetState
so.topic: reference
---

# SetState(Integer state)

Current state of this quote version.

**Parameter:** 
 - **state** Integer
     - Enum: 0 = Unknown 
     - Enum: 1 = Draft 
     - Enum: 2 = DraftNotCalculated 
     - Enum: 3 = DraftNeedsApproval 
     - Enum: 4 = DraftApproved 
     - Enum: 5 = DraftNotApproved 
     - Enum: 6 = Sent 
     - Enum: 7 = Archived 
     - Enum: 8 = Lost 
     - Enum: 9 = Sold 

```crmscript
NSQuoteVersion thing;
Integer state;
thing.SetState(state);
```

