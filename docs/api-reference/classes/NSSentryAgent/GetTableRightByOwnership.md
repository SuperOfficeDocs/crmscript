﻿---
uid: crmscript_ref_NSSentryAgent_GetTableRightByOwnership
title: NSTableRight GetTableRightByOwnership(String tableName, Integer contactGroupId, Integer contactAssociateId)
intellisense: NSSentryAgent.GetTableRightByOwnership
keywords: NSSentryAgent, GetTableRightByOwnership
so.topic: reference
---

Return the NSTableRight from the relationship between the current user and the given user and group.

**Parameters:**
 - **tableName** Name of the table to get the TableRights from.
 - **contactGroupId** The user-group that the associate id is part of.
 - **contactAssociateId** The associate id of the owner of the record

**Returns:** NSTableRight

```crmscript
NSSentryAgent agent;
String tableName;
Integer contactGroupId;
Integer contactAssociateId;
NSTableRight res = agent.GetTableRightByOwnership(tableName, contactGroupId, contactAssociateId);
```

