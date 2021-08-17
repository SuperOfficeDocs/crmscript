---
uid: crmscript_ref_Date_getWeek
title: Date.getWeek()
intellisense: Date.getWeek
sortOrder: 202
keywords: getWeek()
so.topic: reference
so.yml: 1
---

# Date.getWeek()

This function will return the iso week number, from 1 to 53.

See http://en.wikipedia.org/wiki/ISO_8601 for detailed info on ISO week numbers.

## Example

    Date d;
    String s = d.getWeek().toString();
    print(s); 28
