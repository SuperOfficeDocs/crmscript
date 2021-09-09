---
uid: crmscript_ref_NSExtAppEntity_SetVisibleIn
title: SetVisibleIn(Integer visibleIn)
intellisense: NSExtAppEntity.SetVisibleIn
keywords: NSExtAppEntity, GetVisibleIn
so.topic: reference
---

# SetVisibleIn(Integer visibleIn)

The application is visible in

## Parameters

* **visibleIn** Integer

### Enum: visibleIn

* 0 = Invisible
* 1 = ToolboxMenu
* 2 = NavigatorButton
* 3 = ViewMenu
* 4 = SelectionTaskCard
* 5 = ContactCard
* 6 = ContactArchive
* 7 = ProjectCard
* 8 = ProjectArchive
* 9 = SaleCard
* 10 = PersonCard
* 11 = ActivityDialog
* 12 = DocumentDialog
* 13 = BrowserPanel
* 14 = ContSelectionTask
* 15 = AppntSelectionTask
* 16 = SaleSelectionTask
* 17 = DocSelectionTask
* 18 = ProjSelectionTask
* 19 = CompanyMinicard
* 20 = ProjectMinicard
* 21 = DiaryMinicard
* 22 = SelectionMinicard
* 23 = ButtonPanelTask
* 24 = AppointmentDialogTask
* 25 = SaleDialogTask
* 26 = DocumentDialogTask
* 27 = PersonDialogTask
* 28 = SaleMinicard
* 29 = SaleArchive
* 30 = AppntSelectionShadowTask
* 31 = SaleSelectionShadowTask
* 32 = DocSelectionShadowTask
* 33 = ProjSelectionShadowTask
* 34 = DiaryArchive
* 35 = SelectionContactArchive
* 36 = SelectionProjectArchive
* 37 = SelectionSaleArchive
* 38 = SelectionAppointmentArchive
* 39 = SelectionDocumentArchive
* 40 = ContSelectionCustomTask
* 41 = AppntSelectionCustomTask
* 42 = SaleSelectionCustomTask
* 43 = DocSelectionCustomTask
* 44 = ProjSelectionCustomTask
* 45 = CustomArchiveMiniCard
* 46 = SelectionCard
* 47 = ReportMinicard
* 48 = QuoteDialog
* 49 = QuoteDialogTask
* 50 = QuoteDialogArchive
* 51 = QuoteLineDialogTask
* 52 = QuoteLineDialog
* 53 = QuoteLineSelectionMainTask
* 54 = QuoteLineSelectionShadowTask
* 55 = SelectionQuoteLineArchive
* 56 = QuoteLineSelectionCustomTask
* 57 = FindSystem
* 58 = MailingSelectionTask
* 59 = ContactSelectionMailingsTask
* 60 = AppointmentSelectionMailingsTask
* 61 = SaleSelectionMailingsTask
* 62 = DocumentSelectionMailingsTask
* 63 = ProjectSelectionMailingsTask
* 64 = QuoteLineSelectionMailingsTask
* 65 = TopPanelNewMenu
* 66 = Dashboard
* 67 = PersonArchive
* 68 = PersonMinicard
* 69 = CompanyCardTask
* 70 = ProjectCardTask

## Example

```crmscript
NSExtAppEntity thing;
Integer visibleIn;
thing.SetVisibleIn(visibleIn);
```
