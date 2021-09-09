---
uid: crmscript_ref_NSFavouriteAgent_ToggleFavourite
title: Bool ToggleFavourite(String tableName, Integer recordId, Integer associateId, String extraInfo)
intellisense: NSFavouriteAgent.ToggleFavourite
keywords: NSFavouriteAgent, ToggleFavourite
so.topic: reference
---

# Bool ToggleFavourite(String tableName, Integer recordId, Integer associateId, String extraInfo)

Toggle a record in a table as a favorite for an associate

**Returns:** Return the new value, true if added, false if removed

## Parameters

| Parameter | Type | Description |
|---|---|---|
| tableName | String | Table name, transformed to and from numeric table id by the service layer. |
| recordId | Integer | |
| associateId | Integer | |
| extraInfo | String | |

## Example

```crmscript
NSFavouriteAgent agent;
String tableName;
Integer recordId;
Integer associateId;
String extraInfo;
Bool res = agent.ToggleFavourite(tableName, recordId, associateId, extraInfo);
```
