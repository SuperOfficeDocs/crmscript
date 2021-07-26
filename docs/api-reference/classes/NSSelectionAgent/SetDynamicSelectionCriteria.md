﻿---
uid: crmscript_ref_NSSelectionAgent_SetDynamicSelectionCriteria
title: NSArchiveRestrictionInfo[] SetDynamicSelectionCriteria(Integer selectionId, NSArchiveRestrictionInfo[] criteria)
intellisense: NSSelectionAgent.SetDynamicSelectionCriteria
keywords: NSSelectionAgent, SetDynamicSelectionCriteria
so.topic: reference
---

Update the criteria for this dynamic selection. Replaces existing criteria with the new values.

**Parameters:**
 - **selectionId** The id of the selection to add members
 - **criteria** Criteria defining the selection result.

**Returns:** Criteria defining the selection result. NULL if this is not a dynamic selection.

```crmscript
NSSelectionAgent agent;
Integer selectionId;
NSArchiveRestrictionInfo[] criteria;
NSArchiveRestrictionInfo[] res = agent.SetDynamicSelectionCriteria(selectionId, criteria);
```

