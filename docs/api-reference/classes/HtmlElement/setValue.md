---
uid: crmscript_ref_HtmlElement_setValue_String_value
title: HtmlElement.setValue(String value)
intellisense: HtmlElement.setValue
sortOrder: 395
keywords: setValue(String)
so.topic: reference
---

# HtmlElement.setValue(String value)

### Void setValue(String value)

Sets the value of a specific element.

```crmscript
HtmlElement selectDate;
selectDate.setValue("2020.09.10");
```

## Mark a checkbox

```crmscript
HtmlElement t;
t.setValue("x_boolean", "1")
```

## Parameters

* String: the value of the element
