# D2 Codex sign-in helper

This repository only hosts `callback.html`, the page Bungie.net redirects to after you approve D2 Codex during sign-in (Bungie requires an HTTPS page).

Signing in is optional: D2 Codex works without it, and signing in adds your live inventory (characters, vault, postmaster, equip and transfer).

What it does: it hands Bungie's one-time sign-in code to the D2 Codex app running **on your own PC** (`127.0.0.1`), then the tab can be closed.

What it doesn't do: it stores nothing, sends nothing anywhere else, loads no other files, and runs a single script pinned by a Content Security Policy.

D2 Codex is a fan-made tool, not affiliated with or endorsed by Bungie.
