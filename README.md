# Revenge Next compatibility bundle v5

Unofficial experimental compatibility build, modified November 11, 2026. Intended for Discord Android 347.12 (347012); full on-device compatibility is not guaranteed.

Bundle URL: https://raw.githubusercontent.com/Cuddled/revenge-next-v5/main/revenge.bundle

SHA-256: b34cc2935759e64b1dc43c991fceb5184aa84cae12abe27961fce65a5c978d04
Size: 533489 bytes.

This is the existing v5 bundle, unchanged. Modifications restore older Toast, FlashList and icon filters and defer Design initialization. Licensed under GNU GPL v3; see LICENSE. Complete corresponding source is source.zip, based on https://github.com/revenge-mod/revenge-bundle-next at commit 01b4561dc751344b71e45f93a9b0e5b37e35ee33 with the v5 compatibility modifications applied. Source includes dependency lockfile and build scripts. Build with Deno: deno install --frozen, then deno run build. Consult the source README and deno.json for build environment requirements. Runtime requires a compatible native Revenge loader inside Discord; this is not a standalone app.

This repository contains only the bundle and accompanying source/license. No SelectiveMediaSaver plugin files or history are included.
