﻿---
uid: crmscript_ref_NSMDOAgent_GetListWithHistory
title: MDOListItem[] GetListWithHistory(String name, Bool forceFlatList, String additionalInfo, Integer[] historyItems, Bool onlyHistory)
intellisense: NSMDOAgent.GetListWithHistory
keywords: NSMDOAgent, GetListWithHistory
so.topic: reference
---

Method to get a MDO list with own history list.

**Parameters:**
 - **name** Conceptual name of the MDO list-
 - **forceFlatList** Force the list to be flat
 - **additionalInfo** Additional info to the MDO provider
 - **historyItems** An array of ids, used to get the history list
 - **onlyHistory** If true, return only history items

**Returns:** Array of MDOListItem

```crmscript
NSMDOAgent agent;
String name;
Bool forceFlatList;
String additionalInfo;
Integer[] historyItems;
Bool onlyHistory;
MDOListItem[] res = agent.GetListWithHistory(name, forceFlatList, additionalInfo, historyItems, onlyHistory);
```

