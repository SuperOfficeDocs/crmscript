# crmscript

Previously contained docs about the SuperOffice CRMScripting language.

This repo is now inactive and will be marked as archived once issues have been migrated to the [superoffice-docs](https://github.com/SuperOfficeDocs/superoffice-docs) repo.

The contents has moved to make it easier for collaboraters to located and work with SuperOffice documentation.

This content now live and breath in the superoffice-docs repo.

This following is a list of actions and migration points of what was moved where.

1. crmscript/docs/ > superoffice-docs/docs/automation/crmscript/
1. Replace toc.yml with 00-custom/toc.yml. Remove ../ prefixes.
1. whats-new/ > superoffice-docs/release-notes/crmscript/. Move the corresponding items from toc.yml to superoffice-docs/release-notes/toc.yml
1. Delete includes/*.md
1. Merge contents of superoffice-docs/docs/automation/crmscript-intro.md with crmscript/overview/index.md
1. crmscript/chatbot > superoffice-docs/docs/automation/chatbot/.
1. Move api-reference/CRMScript.Event.yml and api-reference/CRMScript.Event.Trigger.yml to automation/trigger/reference/.
1. persons-and-organizations/ > contact/howto/crmscript/
1. follow-ups/ > diary/howto/crmscript/
1. documents/ > document/howto/crmscript/
1. projects/ > project/howto/crmscript/
1. quotes/ > quote/howto/crmscript/
1. sales/ > sale/howto/crmscript/
1. requests/ > requests/howto/crmscript/.
1. Update tocs to reflect the above moves.
1. Move contents of custom-database:
  - extra-fields.md > custom-objects/extra-fields/howto/crmscript/index.md
  - extra-tables.md > custom-objects/extra-tables/howto/crmscript/index.md
  - udef.md > custom-objects/udef/howto/crmscript/index.md
  - sort-extra-field-values.md > custom-objects/extra-fields/howto/crmscript/sort-extra-field-values.md
