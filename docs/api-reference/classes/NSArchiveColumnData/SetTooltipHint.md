---
uid: crmscript_ref_NSArchiveColumnData_SetTooltipHint
title: SetTooltipHint(String tooltipHint)
intellisense: NSArchiveColumnData.SetTooltipHint
keywords: NSArchiveColumnData, GetTooltipHint
so.topic: reference
---

# SetTooltipHint(String tooltipHint)

The tooltip hint is either a text to be shown (after resource tag substitution), or a tooltip key to be given to the tooltip provider system in order to asynchronoously retrieve the actual tooltip.

**Parameter:** 
 - **tooltipHint** String

```crmscript
NSArchiveColumnData thing;
String tooltipHint;
thing.SetTooltipHint(tooltipHint);
```

