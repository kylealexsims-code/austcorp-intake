# AustCorp intake form

The candidate intake form used by the AustCorp `cv` skill. The skill sends a few
lines into the chat that load `hvac-au.js` from jsDelivr, so the form appears
instantly instead of being typed out each time.

One file per market. Edit the market pack in the skill (`assets/markets/`), run
`python3 scripts/build_widget.py <market>`, and copy the built script here as
`<market>.js`. No candidate data is ever stored here.
