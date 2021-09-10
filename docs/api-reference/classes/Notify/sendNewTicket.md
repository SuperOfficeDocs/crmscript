---
uid: crmscript_ref_Notify_sendNewTicket_Integer_ticketId
title: Notify.sendNewTicket(Integer ticketId)
intellisense: Notify.sendNewTicket
keywords: sendNewTicket(Integer), sendNewTicket(Integer,Bool)
so.topic: reference
---

# Notify.sendNewTicket()

This method will send a notification about a new request according to the user's notify configuration.
By setting the parameter skipCategoryMemberNotification, this method will not notify members of the category (if set up) or the "email address" freetext field on the category.

## Methods
* Notify.sendNewTicket(Integer ticketId)
* Notify.sendNewTicket(Integer ticketId, Bool skipCategoryMemberNotification)

## Parameters

 - ticketId: the id of the ticket to notify about

