---
uid: crmscript_ref_NSSelectionEntity_GetLastMembershipChange
title: DateTime GetLastMembershipChange()
intellisense: NSSelectionEntity.GetLastMembershipChange
keywords: NSSelectionEntity, GetLastMembershipChange
so.topic: reference
---

# DateTime GetLastMembershipChange()

The date/time the membership the selection last changed. Dynamic: change of criteria; Static: add/remove members; Combined: change of algorithm

**Returns:** DateTime

```crmscript
NSSelectionEntity thing;
DateTime lastMembershipChange  = thing.GetLastMembershipChange();
```

