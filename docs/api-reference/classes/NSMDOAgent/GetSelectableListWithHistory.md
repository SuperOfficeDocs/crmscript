﻿---
uid: crmscript_ref_NSMDOAgent_GetSelectableListWithHistory
title: SelectableMDOListItem[] GetSelectableListWithHistory(String name, Bool forceFlatList, String additionalInfo, Integer[]historyItems, Bool onlyHistory)
intellisense: NSMDOAgent.GetSelectableListWithHistory
keywords: NSMDOAgent, GetSelectableListWithHistory
so.topic: reference
---

Method to get a Selectable MDO list with own history list.

**Parameters:**
 - **name** Conceptual name of the MDO list.
 - **forceFlatList** Force the list to be flat
 - **additionalInfo** Additional info to the MDO provider
 - **historyItems** An array of ids, used to get the history list
 - **onlyHistory** If true, return only history items

**Returns:** Array of SelectableMDOListItem

```crmscript
NSMDOAgent agent;
String name;
Bool forceFlatList;
String additionalInfo;
Integer[]historyItems;
Bool onlyHistory;
SelectableMDOListItem[] res = agent.GetSelectableListWithHistory(name, forceFlatList, additionalInfo, historyItems, onlyHistory);
```

