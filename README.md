# iframe-demo

Embeds the [Pizza Order Demo](https://victorhuangwq.github.io/pizza-order-demo/) in a full-page iframe.

**Live:** https://victorhuangwq.github.io/iframe-demo/

## Run locally

Open `index.html` in a browser. There's no build step and no dependencies.

## Embed a different page

Change the iframe `src` in [`index.html`](index.html). The target must allow framing. If it doesn't load, check its `X-Frame-Options` and `Content-Security-Policy: frame-ancestors` headers.
