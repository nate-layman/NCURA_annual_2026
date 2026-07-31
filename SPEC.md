# NCURA Annual 2026 - Vandalizer Demo Page

## Goal

A single static page served via GitHub Pages. Attendees land on it during the "Demo Local Vandalizer!" segment and get two things:

1. **Wi-Fi credentials** (SSID + password + QR code) so they can connect fast.
2. **One zip download** containing every example PDF, so they can grab it once and then upload individual files into Vandalizer (https://vandalizer.uidaho.edu) to try the tool live.

That's it. No card grids, no per-file downloads, no nav.

## Page content

Single-page layout, top to bottom:

1. **Heading:** "Demo Local Vandalizer!"
2. **Wi-Fi block** - QR code image + credentials as fallback text:
   - QR: [sparky_wifi.png](sparky_wifi.png) (scan-to-join)
   - **Network:** `sparky`
   - **Password:** `Q3HcMZJ3SE3NsXBQ`
   - **Security:** WPA
3. **Vandalizer launch link/button** pointing to https://vandalizer.uidaho.edu.
4. **Documents zip** - one prominent "Download example documents" button linking to `vandalizer-demo-docs.zip`. The zip includes 6 sample PDFs for testing Vandalizer workflows.

## Documents to include in the zip

From [documents/](documents/):

- `NCOD_Grant_NOFO_2026.pdf`
- `nsf_award_notice_DEB-2412345.pdf`
- `nsf_award_notice_EAR-2418901.pdf`
- `nsf_award_notice_OPP-2345678.pdf`
- `fbu_budget_justification.pdf`
- `fbu_research_strategy.pdf`

Build with: `cd documents && zip ../docs/vandalizer-demo-docs.zip *.pdf`

## GitHub Pages setup

- Serve from `/docs` (GitHub repo Settings > Pages > Source: `main` branch, `/docs` folder).
- Files that need to exist under `docs/`:
  - `docs/index.html` - the page
  - `docs/sparky_wifi.png` - move from repo root
  - `docs/vandalizer-demo-docs.zip` - the bundled PDFs
- Optional: keep `documents/` at the repo root as the "source of truth" for the PDFs, and treat `docs/vandalizer-demo-docs.zip` as a build artifact regenerated when the source PDFs change.

## Still to do

- [ ] Create `docs/index.html` with the four blocks above.
- [ ] Move `sparky_wifi.png` to `docs/`.
- [ ] Build `docs/vandalizer-demo-docs.zip` from `documents/`.
- [ ] Enable GitHub Pages on the repo (Settings > Pages, `main` branch, `/docs` folder).
- [ ] Verify the published URL works and the zip downloads correctly.

## Reference

- Vandalizer live: https://vandalizer.uidaho.edu
- REACH companion site (for optional styling inspiration): https://github.com/ui-insight/REACHWorkshop2026
