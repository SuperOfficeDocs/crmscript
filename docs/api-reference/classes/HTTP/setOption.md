---
uid: crmscript_ref_HTTP_setOption_String_name_String_value
title: HTTP.setOption(String name, String value)
intellisense: HTTP.setOption
sortOrder: 417
keywords: setOption(String,String)
so.topic: reference
---

# HTTP.setOption(String name, String value)

Option function.

## Parameters

| Name | Value | Description |
|---|---|---|
| verifyPeer | bool | verify the peer's SSL certificate |
| verifyHost | bool | verify the certificate's name against the host |
| timeout | | int | set maximum time the request is allowed to take |
| followLocation | bool | follow HTTP 3xx redirects if set to 1, default is 0 |
| username | string | username used in authentication |
| password | string | password used in authentication |
| parameters | string | The complete parameters to post. This will replace whatever you have added using .setValue(), but allows you to specify the whole parameter to post. Useful when posting e.g. JSON structs instead of name=value pairs. NOTE: you need to prefix whatever you want to send with a dummy character (which will be removed) due to complexities in this class. See the example below. |
| authenticationMethod | which authentication method to use.<br>basic (default), digest, gssnegotiate, ntlm, digest_ie, ntlm_wb, none |
| parametersUTF8 | bool. | From version 8.2R3. This option makes the parameters be encoded as UTF-8. Normally this is what you want, but to not break any old uses, this is an optional option. |

## Example

```crmscript
HTTP h;

h.addHeader("header", "test");
h.setValue("key", "value");
h.setValue("key2", "value2");
h.setOption("followLocation", "true");

Byte[] b = h.post("https://httpbin.org/post");

if (h.hasError())
  print(h.getErrorMessage());
else
  print(String(b));

//Here is an example for creating an issue in JIRA, hosted by Atlassian

HTTP h2;
String json = " {
  "fields": {
    "project": {
      "key": "SUP"
    },
"summary": "I have a problem!.",
"description": "Thats awesome",
    "issuetype": {
      "name": "Bug"
    }
  }
}";

HTTP h;
h.setOption("username", "theUsername");
h.setOption("password", "thePassword");
h.addHeader("Content-Type", "application/json");
h.setOption("parameters", json);
print(String(h.post("https://theInstance.atlassian.net/rest/api/2/issue/")));
```
