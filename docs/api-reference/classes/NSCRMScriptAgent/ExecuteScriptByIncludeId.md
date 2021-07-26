﻿---
uid: crmscript_ref_NSCRMScriptAgent_ExecuteScriptByIncludeId
title: String ExecuteScriptByIncludeId(String cRMScriptIncludeId, StringDictionary parameters)
intellisense: NSCRMScriptAgent.ExecuteScriptByIncludeId
keywords: NSCRMScriptAgent, ExecuteScriptByIncludeId
so.topic: reference
---

Execute a CRMScript with parameters, returning printed output value.

**Parameters:**
 - **cRMScriptIncludeId** The include id of the CRMScript to validate
 - **parameters** Parameters passed as variables to the CRMScript

**Returns:** String

```crmscript
NSCRMScriptAgent agent;
String cRMScriptIncludeId;
StringDictionary parameters;
String res = agent.ExecuteScriptByIncludeId(cRMScriptIncludeId, parameters);
```

