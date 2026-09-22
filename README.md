# ACMS Player Portal v2.29

GitHub Pages deployment package for the ACMS Inter-Hospital Pickleball Tournament Player Portal.

## Changes in v2.29
- Uses the full available desktop viewport instead of limiting the application to a 1460px content width.
- Narrows the shared sponsor/search rail slightly so the tournament workspace receives more horizontal space.
- Reworks the Player Portal QR card into a compact horizontal layout with a much smaller QR code.
- Keeps Find My Matches, Major Sponsors, Secondary Sponsors and the QR card available across all Player Portal pages.
- Preserves the existing Supabase live-sync configuration.

## Deploy
Upload the files in this folder directly to the root of the `ACMS_InterHospital` GitHub repository.

The browser-safe Supabase publishable key may be deployed with this Player Portal. Never add a Supabase secret key, database password or the private ACMS `acms_...` publish key to this repository.


## v2.29 layout update
On desktop, the Player Portal QR card now expands to fill the remaining height of the shared left rail. The QR is centered and scales up within that available space, eliminating the unused vertical gap below the sponsor cards. Mobile/tablet behavior remains compact.
