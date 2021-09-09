---
uid: crmscript_ref_Ticket_setValue_String_colName_String_value
title: Ticket.setValue(String colName, String value)
intellisense: Ticket.setValue
keywords: setValue(String,String)
so.topic: reference
---

# Ticket.setValue(String colName, String value)

Sets column colName to the given value.
Obs: For this to actually affect the ticket, you will have to use the function `save()` after you have set all the values you want.

## Parameters

| Parameter | Type | Description |
|---|---|---|
| colName | String | |
| value | String | A String representation of the value to set. |

### Values

Possible values are the extrafields on the ticket and the following:

* title
* category: the category id
* ownedBy: (owned_by), the id of the user who owns the ticket
* slevel: the security level of the ticket, 1 is internal, 2 is external
* priority: the id
* status: 1 = active, 2 = closed, 3 = postponed, 4 = deleted, 5 = composed
* ticketStatus: (ticket_status), the id of the custom status field
* custId: the id of the primary customer
* customers: comma separated list of customer ids
* createdBy: the id of the user who posted the ticket, 1 if the ticket is posted into the system
* author: a string containing the name of the ticket author
* activate: the datetime when the ticket was activated
* createdAt: (created_at), the datetime when the ticket was created
* repliedAt: (replied_at), the datetime when the ticket first was replied at
* stopEscalation
* readStatus (read_status)
* deadline
* filterAddress
* timeToClose
* realTimeToClose
* dbiAgentId
* dbiKey
* dbiLastModified
* dbiLastSyncronized
