﻿---
uid: crmscript_ref_NSDocumentAgent_GetVersionList
title: VersionInfo[] GetVersionList(Integer documentId)
intellisense: NSDocumentAgent.GetVersionList
keywords: NSDocumentAgent, GetVersionList
so.topic: reference
---

Get a list of existing, committed  versions for a given document

**Parameters:**
 - **documentId** SuperOffice document Id

**Returns:** Array of objects describing the existing, committed versions for this document

```crmscript
NSDocumentAgent agent;
Integer documentId;
VersionInfo[] res = agent.GetVersionList(documentId);
```

