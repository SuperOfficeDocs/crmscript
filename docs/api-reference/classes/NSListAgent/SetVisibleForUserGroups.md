﻿---
uid: crmscript_ref_NSListAgent_SetVisibleForUserGroups
title: SelectableMDOListItem[] SetVisibleForUserGroups(Integer udListDefinitionId, Integer listItemId, SelectableMDOListItem[] userGroups)
intellisense: NSListAgent.SetVisibleForUserGroups
keywords: NSListAgent, SetVisibleForUserGroups
so.topic: reference
---

Update User groups that this list item is visible for

**Parameters:**
 - **udListDefinitionId** The id of the list. Negative numbers indicate TableNumber value instead of UDListDefId. e.g. -64 = category.
 - **listItemId** The id of the list item
 - **userGroups** The selectable user groups.

**Returns:** Array of selectable user groups

```crmscript
NSListAgent agent;
Integer udListDefinitionId;
Integer listItemId;
SelectableMDOListItem[] userGroups;
SelectableMDOListItem[] res = agent.SetVisibleForUserGroups(udListDefinitionId, listItemId, userGroups);
```

