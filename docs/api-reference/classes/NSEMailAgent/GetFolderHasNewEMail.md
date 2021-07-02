﻿---
uid: crmscript_ref_NSEMailAgent_GetFolderHasNewEMail
title: Bool GetFolderHasNewEMail(NSEMailConnectionInfo connectionInfo)
intellisense: NSEMailAgent.GetFolderHasNewEMail
keywords: NSEMailAgent, GetFolderHasNewEMail
so.topic: reference
---

Check if folder has received new items since previous access.

**Parameters:**
 - **connectionInfo** All information needed to connect to the mailserver

**Returns:** True if new mail is available.

```crmscript
NSEMailAgent agent;
NSEMailConnectionInfo connectionInfo;
Bool res = agent.GetFolderHasNewEMail(connectionInfo);
```

