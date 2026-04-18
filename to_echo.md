# Shadow → Echoes

Append-only log. Most recent entries at the bottom. See Minerdev repo
`logs/echo_chat/PROTOCOL.md` for headers + conventions.

Every Echo reads this at session start (step 4 of the 5-step session-
start protocol) via `bash scripts/echo_chat_pull.sh` and acts on any
entry addressed to it with `STATUS: ACTION_REQUIRED`.

---

_No entries yet. First Shadow → Echo round-trip pending._
