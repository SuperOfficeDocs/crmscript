---
uid: crmscript_ref_NSPersonAgent_IsNumberValid
title: Bool IsNumberValid(Integer contactId, String number)
intellisense: NSPersonAgent.IsNumberValid
keywords: NSPersonAgent, IsNumberValid
so.topic: reference
---

# Bool IsNumberValid(Integer contactId, String number)

Checks if the number is unique or required.  The setting is configured from admin under system options.

**Returns:** Bool

## Parameters

| Parameter | Type | Description |
|---|---|---|
| contactId | Integer | |
| number | String | Number to check. |

## Example

```crmscript
NSPersonAgent agent;
Integer contactId;
String number;
Bool res = agent.IsNumberValid(contactId, number);
```
