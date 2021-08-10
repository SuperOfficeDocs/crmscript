---
uid: crmscript_ref_NSContactActivity_GetActionTime
title: DateTime GetActionTime()
intellisense: NSContactActivity.GetActionTime
keywords: NSContactActivity, GetActionTime
so.topic: reference
---

# DateTime GetActionTime()

The time of the activity. If more than one activity has occured on the contact, the last activity time is shown.

**Returns:** DateTime

```crmscript
NSContactActivity thing;
DateTime actionTime  = thing.GetActionTime();
```

