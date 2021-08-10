---
uid: crmscript_ref_HTTP_patchAsStream_String_p_0
title: HTTP.patchAsStream(String p_0)
intellisense: HTTP.patchAsStream
sortOrder: 408
keywords: patchAsStream(String)
so.topic: reference
---

# HTTP.patchAsStream(String p_0)

Supports both http and https. Returns the result in a NSStream.

## Example

    HTTP h;
    
    h.addHeader("header", "test");
    h.setValue("key", "value");
    h.setValue("key2", "value2");
    h.setOption("followLocation", "true");
    NSStream b = h.patchAsStream("https://httpbin.org/patch");
    if (h.hasError())
      print(h.getErrorMessage());
    else
      print(String(b));

