﻿---
uid: crmscript_class_nscontactagent_getaddressbycountry
title: Address GetAddressByCountry()
description: CRMScript method in the NSContactAgent class that gets a contact's localized address
intellisense: NSContactAgent.GetAddressByCountry
keywords: NSContactAgent, GetAddressByCountry, GetAddressByCountry(Integer,Integer)
so.topic: reference
---

# GetAddressByCountry()

Gets the contact's localized address (LocalizedField[][]).

`Address GetAddressByCountry(Integer contactId, Integer countryId)`

## Parameters

| contactId | Integer | The contact ID |
| countryId | Integer | |

## Examples

```crmscript
NSContactAgent agent;
Integer contactId;
Integer countryId;
Address res = agent.GetAddressByCountry(contactId, countryId);
```
