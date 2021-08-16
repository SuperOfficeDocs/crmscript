---
uid: crmscript_ref_Category_load_Integer_id
title: Category.load(Integer id)
intellisense: Category.load
sortOrder: 151
keywords: load(Integer)
so.topic: reference
---

# Category.load(Integer id)

Load object with values from category with given id.

## Parameters

 - id: The id of the category to load.

Returns true if the category exists, otherwise false.

## Example

    Category c;
    
    c.load(2);
    print(c.getValue("name"));

