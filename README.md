# Pixel Activation Page

A static page that installs the TikTok (and optional Snapchat) pixel base code and
fires standard browser events on load, so the integration registers with a real
domain over HTTPS. Intended for **validating** a pixel setup — not for generating
fake conversion volume.

## Use
Open the deployed URL in a browser. The TikTok base code auto-installs and fires
`page()` + standard events. Add a Snapchat Pixel ID in the form to enable Snapchat.

## Deploy
Static site — deploys as-is on Vercel (no build step).
