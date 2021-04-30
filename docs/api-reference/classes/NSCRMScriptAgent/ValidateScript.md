﻿---
uid: crmscript_ref_NSCRMScriptAgent_ValidateScript
title: CRMScriptResult ValidateScript(Integer cRMScriptId)
intellisense: NSCRMScriptAgent.ValidateScript
keywords: NSCRMScriptAgent, ValidateScript
so.topic: reference
---

Validate a CRMScript. This will check that the syntax is correct

**Parameters:**
 - **cRMScriptId** The id of the CRMScript to execute

**Returns:** True of the syntax is correct

```crmscript
NSCRMScriptAgent agent;
Integer cRMScriptId;
CRMScriptResult res = agent.ValidateScript(cRMScriptId);
```
