---
uid: crmscript_ref_NSStatusMonitor_GetNumMatches
title: Integer GetNumMatches()
intellisense: NSStatusMonitor.GetNumMatches
keywords: NSStatusMonitor, GetNumMatches
so.topic: reference
---

# Integer GetNumMatches()

Number of targets that have this status, this should be the number of rows in StatusValue pointing to this definition, and that have isSignalled set to 1

**Returns:** Integer

```crmscript
NSStatusMonitor thing;
Integer numMatches  = thing.GetNumMatches();
```

