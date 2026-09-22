# ACMS Player Portal v2.33

This build preserves the approved 230px × 300px Player Portal QR card and Supabase live sync.

## Sponsor update
Added the supplied sponsor creatives to the Secondary Sponsors rotation:
- UNILAB ImmunPro Prime
- UNILAB Etoricoxib Myox
- Kassa Media

The assets are stored under `assets/sponsors/` and are referenced by `index.html`.

# ACMS Player Portal v2.32

GitHub Pages deployment package for the ACMS Inter-Hospital Pickleball Tournament Player Portal.

## Current build
- Shared left rail is available across all Player Portal pages.
- Includes Find My Matches, Major Sponsors, Secondary Sponsors, and Player Portal QR.
- Desktop workspace uses the full available viewport width.
- Desktop Player Portal QR card is fixed at **230px wide × 300px high**.
- Tablet/mobile retain the compact responsive treatment.
- Supabase live-sync configuration is included through `acms-sync-config.json`.
- Player Portal URL encoded in the QR: `https://qourts.github.io/ACMS_InterHospital/`.

## Deploy
Upload the files inside this package directly to the root of the `ACMS_InterHospital` GitHub repository, replacing the existing files.

Expected root files:
- `index.html`
- `acms-sync-config.json`
- `.nojekyll`
- `README.md`

## Security
The browser-safe Supabase publishable key is included in `acms-sync-config.json` and is intended for client-side use. Never add a Supabase secret key, database password, or the private ACMS `acms_...` publish key to this repository.
