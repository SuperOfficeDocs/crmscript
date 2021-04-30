﻿---
uid: crmscript_ref_NSProjectEventEntity_SetVisibleForPersonInterests
title: SetVisibleForPersonInterests(MDOListItemArray visibleForPersonInterests)
intellisense: NSProjectEventEntity.SetVisibleForPersonInterests
keywords: NSProjectEventEntity, GetVisibleForPersonInterests
so.topic: reference
---

Array of person interests (MDO table "persint") that this event is visible for.

**Parameter:** 
 - **visibleForPersonInterests** MDOListItemArray

```crmscript
NSProjectEventEntity thing;
MDOListItemArray visibleForPersonInterests;
thing.SetVisibleForPersonInterests(visibleForPersonInterests);
```
