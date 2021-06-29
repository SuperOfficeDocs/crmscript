﻿---
uid: crmscript_ref_NSViewStateAgent_SaveHistories
title: History[] SaveHistories(String historyName, History[] history)
intellisense: NSViewStateAgent.SaveHistories
keywords: NSViewStateAgent, SaveHistories
so.topic: reference
---

Replaces the existing history-list for the currently logged in user. All elements must belong to the same history list. If not they are ignored.

**Parameters:**
 - **historyName** 
 - **history** Array of new history items to save.

**Returns:** Array of the saved History items

```crmscript
NSViewStateAgent agent;
String historyName;
History[] history;
History[] res = agent.SaveHistories(historyName, history);
```

