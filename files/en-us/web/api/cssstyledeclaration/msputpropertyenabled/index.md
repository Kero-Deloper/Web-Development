---
title: CSSStyleDeclaration.msPutPropertyEnabled()
slug: Web/API/CSSStyleDeclaration/msPutPropertyEnabled
page-type: web-api-instance-method
status:
  - non-standard
---

{{APIRef("HTMLMediaElement")}}

{{Non-standard_header()}}

The **`msPutPropertyEnabled()`** method sets whether a given property in the style object is enabled or disabled.

This proprietary method is specific to Internet Explorer and Microsoft Edge.

### Syntax

```js-nolint
msPutPropertyEnabled(name, boolean)
```

### Parameters

name\[in]: Name of the property. (String)

boolean\[in]: True = Enable the property. False = Disable the property.

### Return value

Type = HRESULT: If this method succeeds, it returns S_OK. Otherwise, it returns an HRESULT error code.

## See also

- [CSS Style Declaration](/en-US/docs/Web/API/CSSStyleDeclaration)
- [Microsoft API extensions](/en-US/docs/Web/API/Microsoft_Extensions)
