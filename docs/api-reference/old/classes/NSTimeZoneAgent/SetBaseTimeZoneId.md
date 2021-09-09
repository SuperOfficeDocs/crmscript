---
uid: crmscript_ref_NSTimeZoneAgent_SetBaseTimeZoneId
title: Bool SetBaseTimeZoneId(Integer timezoneId)
intellisense: NSTimeZoneAgent.SetBaseTimeZoneId
keywords: NSTimeZoneAgent, SetBaseTimeZoneId
so.topic: reference
---

# Bool SetBaseTimeZoneId(Integer timezoneId)

Set the base timezone id.

**Returns:** Bool

## Parameters

| Parameter | Type | Description |
|---|---|---|
| timezoneId | Integer | The timezone id to save |

## Example

```crmscript
NSTimeZoneAgent agent;
Integer timezoneId;
Bool res = agent.SetBaseTimeZoneId(timezoneId);
```
