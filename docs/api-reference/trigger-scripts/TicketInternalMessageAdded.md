---
title: triggerscripts
description: Trigger scripts
so.author: Christian Mogensen
so.date: 11.11.2020
keywords:
---

# TicketInternalMessageAdded (151)

Called for all internal messages added to a ticket, following a call to the `TicketMessageAdded` trigger.

## Input values
|Variable|Description|
|---|---|
| `entryId` | the ticket ID|
| `ticketId` | the ticket ID|
| `messageId` | the ticket message ID|

## Sample code

```crmscript
#setLanguageLevel 3;
String param1 = getVariable("entryId");
```
