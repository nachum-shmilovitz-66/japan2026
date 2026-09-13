# japan2026.xyz

A travel plan for Michal and Nachum, 3–27 November 2026 — Osaka to Tokyo the long
way round, down the Hokuriku coast and over the mountains through Takayama.

`index.html` is one self-contained file. No build step, no dependencies, no
network calls beyond the web fonts. Save it and it still works on a plane.

It is generated from a private source by `make_public.py`, which strips out the
reservation numbers, PINs, ticket numbers and licence numbers that the private
copy carries for the travellers' own use. Nothing here is confidential.

English and Hebrew, light and dark, and a route map drawn as inline SVG so it
works with no signal.

## Where it is served

<https://japan2026.xyz>, from Cloudflare Pages. This repository is the source of
record for the public copy; it no longer serves the site itself, so there is no
GitHub Pages deployment and no `CNAME` file.

## Android

The releases here carry `Japan-2026-public.apk` — the same page wrapped as an
app, so it opens from the launcher and works with no signal. It installs
alongside anything else and asks for no permissions.
