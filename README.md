# overcast_isomer releases

The built web client of Overcast, a multi-cloud cost and resource dashboard, from its Isomer host (overcast_isomer, a private repo). GitHub Pages serves it at https://attilathefun.github.io/overcast_isomer_releases/. It is a wasm app and a small HTML shell, published by the source repo's `tools/publish_web.sh`. This repo holds compiled output only, not the source.

**This copy is demo-only.** Cloud provider APIs send no CORS headers, so the real web client runs from Overcast's local dev server, which proxies requests and keeps credentials in the macOS Keychain. Served from here there is no such server, so the page sends nothing to this host, never transmits a credential, and shows sample data: enter `demo` as any provider's key. For real accounts, use the Mac app or run the web client locally.
