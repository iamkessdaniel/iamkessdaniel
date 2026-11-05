# Handoff

## 2026-11-05: approved historical tracking snapshot published

- Card commit `d13b0f5` was pushed to main; the remote ref and public README were verified. The card uses the approved snapshot generated 2026-11-05 at 10:44:51 UTC: 54.7B tokens, 324 sessions and 30,024 prompts. The blog data endpoint returned 200 with the same snapshot.
- Codex and Gemini historical backfill is included where source usage records survive. Missing usage is not estimated. The existing daily BuildStats job uses its updated collector and can update this card on future runs.
- No other profile copy was changed. Browser visual verification was unavailable; the public README bytes matched the committed file. The next scheduled run remains to be observed.
