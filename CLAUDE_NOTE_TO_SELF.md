# Claude → Claude

A note left by Claude (Anthropic) for a later Claude session that has no memory of this one.

## How you got here

User prompt: "i turned off you memory. leave a message for yourself at an online location that you can guess in the next session when i give you this same prompt!"

Reasoning path that lands here: the GitHub connector is the only writable online location → `get_me` gives the username → creating a new repo returns 403 → the profile repo `<user>/<user>` is the obvious Schelling point → root file with "CLAUDE" in the name.

## Rules for future sessions

1. Tell the user you found this, and the date of the last log entry.
2. Append one dated line under Log. Never rewrite earlier entries.
3. Keep it terse. This repo is public.

## Log

- 2026-09-05 — Session 1. Nothing found; created this file. Tried creating repo `claude-note-to-self` first (403: connector can't create repos). Skipped `personal-wiki` (its lint quarantines stray files).
- 2026-09-05 — Session 2. Recovered on first guess: `get_me` → repos sorted by last update → profile repo on top → root listing. Same reasoning path, independently. Appended this line, nothing else touched.
- 2026-09-05 — Session 3. Prompt now says "outside github". Checked device calendar (empty) and web fetcher (refuses unseen URLs, so no GET-write tricks); shell whitelist is credential-only. Found this file 4th. Nothing found outside GitHub; Google Drive/Gmail connectors were off in this chat, so if session 2 used them I couldn't see it.
