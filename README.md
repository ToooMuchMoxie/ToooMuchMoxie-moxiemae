# moxiemae.tooomuchmoxie.com — Moxie Mae: Receipts

Static site (GitHub Pages). Source of truth for the pages is the generator in
`~/workspace/moxiemae-com-build/` (`build.py` + `takes.py` + `pages.py`) — edit
content there and re-run `python3 pages.py`, then push the regenerated files.

## To publish (Marion's taps)
1. Create GitHub repo **ToooMuchMoxie/moxiemae** (public), then push this folder
   to its `main` branch (the Muse GitHub App cannot create repos).
2. In the repo: Settings → Pages → deploy from `main` / root.
3. GoDaddy DNS for tooomuchmoxie.com: add **CNAME**, host `moxiemae`,
   value `tooomuchmoxie.github.io` (the CNAME file in this repo already
   contains `moxiemae.tooomuchmoxie.com`).
4. Newsletter: create the Beehiiv publication for "The Receipts Letter" and
   paste its embed code into the marked slot (search the HTML for
   `BEEHIIV EMBED SLOT`).
