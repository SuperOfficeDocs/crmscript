﻿---
uid: crmscript_ref_NSEMailConnectionInfoExtended_SetServerName
title: SetServerName(String serverName)
intellisense: NSEMailConnectionInfoExtended.SetServerName
keywords: NSEMailConnectionInfoExtended, GetServerName
so.topic: reference
---

Hostname or ip to server to connect to. Custom ports may be specified by adding ':' and the port number after the name/ip. Ex: '127.0.0.1:6543'

**Parameter:** 
 - **serverName** String

```crmscript
NSEMailConnectionInfoExtended thing;
String serverName;
thing.SetServerName(serverName);
```
