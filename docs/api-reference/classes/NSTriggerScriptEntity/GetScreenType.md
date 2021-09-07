---
uid: crmscript_ref_NSTriggerScriptEntity_GetScreenType
title: Integer GetScreenType()
intellisense: NSTriggerScriptEntity.GetScreenType
keywords: NSTriggerScriptEntity, GetScreenType
so.topic: reference
---

# Integer GetScreenType()

Event id that triggers script.

**Returns:** Integer

## Enum: eventHandlerType

* 0 = Unknown
* 100 = NewTicket
* 101 = NewTicketFromCustomerCenter
* 102 = NewTicketFromEmail
* 103 = NewTicketFromCustomerCenterBeforeSave
* 104 = NewTicketFromSpmLink
* 105 = NewNotifyTicketFromForm
* 106 = NewTicketFromForm
* 109 = TicketSave
* 110 = TicketClosed
* 111 = TicketPostponed
* 112 = TicketDeleted
* 113 = TicketActivated
* 120 = TicketReopened
* 121 = TicketReopenedFromCustomerCenter
* 122 = TicketReopenedFromEmail
* 140 = TicketChangedPriority
* 141 = TicketChangedCategory
* 142 = TicketChangedOwnedBy
* 143 = TicketChangedPrimaryCustomer
* 144 = TicketChangedTicketStatus
* 145 = TicketChangedSlevel
* 150 = TicketMessageAdded
* 151 = TicketInternalMessageAdded
* 152 = TicketExternalMessageAdded
* 153 = TicketMessageSentimentCalculated
* 200 = CompactModeInjection
* 210 = CustomerCenterAuthentication
* 300 = ScheduledTaskFailed
* 301 = DbiTaskFailed
* 302 = CustomerSetSubscriptions
* 303 = ImportMailBeforeProcessing
* 304 = ImportMailAfterProcessing
* 305 = MainMenu
* 400 = ChatNewSession
* 401 = ChatSessionChangedStatus
* 402 = ChatBeforeSaveNewMessage
* 403 = ChatAfterSaveNewMessage
* 500 = ServiceScreenNewTicketLoad
* 501 = ServiceScreenNewQuickTicketLoad
* 502 = ServiceScreenListTicketMessagesLoad
* 503 = ServiceScreenAddMessageLoad
* 504 = ServiceScreenEditTicketLoad
* 505 = ServiceScreenViewCustomerLoad
* 506 = ServiceScreenEditCustomerLoad
* 507 = ServiceScreenViewCompanyLoad
* 508 = ServiceScreenEditCompanyLoad
* 509 = ServiceScreenForwardLoad
* 510 = ServiceScreenEditExtraTableLoad
* 600 = ServiceScreenNewTicketBeforeSubmit
* 601 = ServiceScreenNewQuickTicketBeforeSubmit
* 602 = ServiceScreenListTicketMessagesBeforeSubmit
* 603 = ServiceScreenAddMessageBeforeSubmit
* 604 = ServiceScreenEditTicketBeforeSubmit
* 605 = ServiceScreenViewCustomerBeforeSubmit
* 606 = ServiceScreenEditCustomerBeforeSubmit
* 607 = ServiceScreenViewCompanyBeforeSubmit
* 608 = ServiceScreenEditCompanyBeforeSubmit
* 609 = ServiceScreenForwardBeforeSubmit
* 610 = ServiceScreenEditExtraTableBeforeSubmit
* 700 = ServiceScreenNewTicketAfterSubmit
* 701 = ServiceScreenNewQuickTicketAfterSubmit
* 702 = ServiceScreenListTicketMessagesAfterSubmit
* 703 = ServiceScreenAddMessageAfterSubmit
* 704 = ServiceScreenEditTicketAfterSubmit
* 705 = ServiceScreenViewCustomerAfterSubmit
* 706 = ServiceScreenEditCustomerAfterSubmit
* 707 = ServiceScreenViewCompanyAfterSubmit
* 708 = ServiceScreenEditCompanyAfterSubmit
* 709 = ServiceScreenForwardAfterSubmit
* 710 = ServiceScreenEditExtraTableAfterSubmit
* 1001 = SalesBeforeSaveAppointment
* 1002 = SalesBeforeSaveStakeholder
* 1003 = SalesBeforeSaveQuote
* 1004 = SalesBeforeSaveDocument
* 1005 = SalesBeforeSaveContact
* 1006 = SalesBeforeSavePerson
* 1007 = SalesBeforeSaveRelation
* 1008 = SalesBeforeSaveSale
* 1009 = SalesBeforeSaveProject
* 1010 = SalesBeforeSaveSelection
* 1011 = SalesBeforeSaveProjectMember
* 1012 = SalesBeforeSaveSelectionMember
* 1013 = SalesBeforeSaveQuoteLine
* 1101 = SalesAfterSaveAppointment
* 1102 = SalesAfterSaveStakeholder
* 1103 = SalesAfterSaveQuote
* 1104 = SalesAfterSaveDocument
* 1105 = SalesAfterSaveContact
* 1106 = SalesAfterSavePerson
* 1107 = SalesAfterSaveRelation
* 1108 = SalesAfterSaveSale
* 1109 = SalesAfterSaveProject
* 1110 = SalesAfterSaveSelection
* 1111 = SalesAfterSaveProjectMember
* 1112 = SalesAfterSaveSelectionMember
* 1113 = SalesAfterSaveQuoteLine

## Example

```crmscript
NSTriggerScriptEntity thing;
Integer screenType  = thing.GetScreenType();
```
