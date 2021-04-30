﻿---
uid: crmscript_ref_NSCustomerServiceAgent_CreateTicketFromMailData
title: TicketInfo CreateTicketFromMailData(Integer mailboxId, String data)
intellisense: NSCustomerServiceAgent.CreateTicketFromMailData
keywords: NSCustomerServiceAgent, CreateTicketFromMailData
so.topic: reference
---

This method create a new ticket in the same way as importMail would import an email. It accepts RFC822 formatted data

**Parameters:**
 - **mailboxId** The id of the Service mailbox
 - **data** RFC822 formatted data to import as a ticket

**Returns:** An object containing some meta data for the created ticket

```crmscript
NSCustomerServiceAgent agent;
Integer mailboxId;
String data;
TicketInfo res = agent.CreateTicketFromMailData(mailboxId, data);
```
