# M06 P02 — registered runtime trigger

Purpose: trigger the default-branch registered `QPS M06 Bounded Observer Smoke` workflow on a clean follow-up PR.

Victory chain:

`exact PR head -> real Telegraf build -> --once -> inputs.exec metric -> outputs.file -> exact receipt -> retained artifact`

No federation or engineering-authority credit is granted by this trigger file itself.
