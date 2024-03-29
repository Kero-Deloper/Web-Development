---
title: VideoEncoder.close()
slug: Web/API/VideoEncoder/close
page-type: web-api-instance-method
status:
  - experimental
browser-compat: api.VideoEncoder.close
---

{{APIRef("WebCodecs API")}}{{SecureContext_Header}}{{SeeCompatTable}}

The **`close()`** method of the {{domxref("VideoEncoder")}} interface ends all pending work and releases system resources.

## Syntax

```js-nolint
close()
```

### Parameters

None.

### Return value

None ({{jsxref("undefined")}}).

## Examples

The following example closes the `VideoEncoder`.

```js
VideoEncoder.close();
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
