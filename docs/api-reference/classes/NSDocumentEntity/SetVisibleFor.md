﻿---
uid: crmscript_ref_NSDocumentEntity_SetVisibleFor
title: SetVisibleFor(NSVisibleFor[] visibleFor)
intellisense: NSDocumentEntity.SetVisibleFor
keywords: NSDocumentEntity, SetVisibleFor
so.topic: reference
---

Set the usergroups and/or users the DocumentEntity item is visible for.

**Parameter:** 
 - **visibleFor** NSVisibleFor[] of one or more users + usergroups.

```crmscript
NSDocumentEntity thing;
NSVisibleFor[] visibleFor = thing.GetVisibleFor();
visibleFor[0].SetVisiblity(1);  // usergroup
visibleFor[0].SetVisibleId(123); // usergroup id
thing.SetVisibleFor(visibleFor);
```

