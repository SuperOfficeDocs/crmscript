---
uid: crmscript_ref_Company_toParser_Parser_parser
title: Company.toParser(Parser parser)
intellisense: Company.toParser
sortOrder: 169
keywords: toParser(Parser)
so.topic: reference
---

# Company.toParser(Parser parser)

This function puts a lot of fields into the input parser.

## Parameters

 - Parser parser: The parser to put the field-value-pairs to.

## Fields that will be loaded

 - company.id: The id
 - company.name: The name
 - company.note: The note
 - company.domain: The domain
 - company.phone: Phone number
 - company.fax: Fax number
 - company.adr: The address
 - company.ourContact: The id of the user that is this company's contact
 - company.primaryContact.id: The id of the customer that is this company's primary contact
 - company.primaryContact.email: The email address of the customer that is this company's primary contact
 - company.extraFieldName: The name of the extrafield, (not x\_fieldname)

