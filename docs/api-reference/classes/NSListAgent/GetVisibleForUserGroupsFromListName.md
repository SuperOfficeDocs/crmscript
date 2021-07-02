﻿---
uid: crmscript_ref_NSListAgent_GetVisibleForUserGroupsFromListName
title: SelectableMDOListItem[] GetVisibleForUserGroupsFromListName(String udListDefinitionName, Integer listItemId)
intellisense: NSListAgent.GetVisibleForUserGroupsFromListName
keywords: NSListAgent, GetVisibleForUserGroupsFromListName
so.topic: reference
---

List of User groups that this list item is visible for

**Parameters:**
 - **udListDefinitionName** The name of the list definition.
 - **listItemId** The id of the list item

**Returns:** Array of selectable user groups

```crmscript
NSListAgent agent;
String udListDefinitionName;
Integer listItemId;
SelectableMDOListItem[] res = agent.GetVisibleForUserGroupsFromListName(udListDefinitionName, listItemId);
```

