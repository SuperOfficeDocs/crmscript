﻿---
uid: crmscript_ref_NSSelectionAgent_SetDynamicSelectionCriteriaGroups
title: ArchiveRestrictionGroup[] SetDynamicSelectionCriteriaGroups(Integer selectionId, ArchiveRestrictionGroup[] criteria)
intellisense: NSSelectionAgent.SetDynamicSelectionCriteriaGroups
keywords: NSSelectionAgent, SetDynamicSelectionCriteriaGroups
so.topic: reference
---

Update the criteria for this dynamic selection. Replaces existing criteria with the new values. This call supports multiple criteria groups.

**Parameters:**
 - **selectionId** The id of the selection to add members
 - **criteria** Criteria groups defining the selection result. Empty array is legal, simply means no criteria have been set

**Returns:** Criteria groups defining the selection result. NULL if this is not a dynamic selection.

```crmscript
NSSelectionAgent agent;
Integer selectionId;
ArchiveRestrictionGroup[] criteria;
ArchiveRestrictionGroup[] res = agent.SetDynamicSelectionCriteriaGroups(selectionId, criteria);
```

