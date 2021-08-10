---
uid: crmscript_ref_NSArchiveListItem_GetStyleHint
title: String GetStyleHint()
intellisense: NSArchiveListItem.GetStyleHint
keywords: NSArchiveListItem, GetStyleHint
so.topic: reference
---

# String GetStyleHint()

Style hint for the row, for instance 'retired' for associates or 'private' for appointments. Presentation layers can interpret the style hints as they see fit.

**Returns:** String

```crmscript
NSArchiveListItem thing;
String styleHint  = thing.GetStyleHint();
```

