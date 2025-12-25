# epoxy-transport

epoxy-transport is a transport for bare-mux which allows you to use [epoxy-tls](https://github.com/MercuryWorkshop/epoxy-tls) in your bare client.

## Usage:
Here is a basic example of using epoxy-transport. The Wisp proxy server is specified in the `wisp` option. 
```js
import { EpoxyClient } from "@mercuryworkshop/epoxy-transport";
let client = new EpoxyClient({ wisp: "wss://example.com/wisp/" });

// pass to proxy
```

You can also use the non-esm build
```html
<script src="https://unpkg.com/@mercuryworkshop/epoxy-transport@3/dist/index.js"></script>
<script>
  let client = new EpoxyTransport.EpoxyClient({ wisp: "wss://example.com/wisp/" });
</script>
```

## Copyright:
This package is licensed under the GNU AGPL v3.
