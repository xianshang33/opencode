# PR 57078 fixture evidence

Synthetic local web-app fixtures only; no personal sessions or provider calls.

- `before-dialog.png`: message-only picker baseline. The title was normalized to “Fork session” for the test fixture; it is not an exact screenshot of the upstream title “Fork from message”.
- `after-dialog.png`: current picker with Full session first, matching the production component tested by the keeper regression.

Screenshots illustrate the UI only, not server history copying. Local core fork tests separately cover independent saved histories and settled messages.
