# Safwan WiFi Website

A responsive, Bengali-first public website starter for Safwan WiFi.

## Current scope
- Responsive landing page
- Internet package information (currently shown: 30 SAR / 30 days)
- Support section
- Mobile navigation

## Important
This is the initial public website frontend only. Customer sign-in, voucher purchase/activation, payments, admin dashboard, database, and live TP-Link Omada controller integration are **not connected yet**. No sample customer records or fake sales are included.

## Deploy with Cloudflare Pages
1. Open Cloudflare Dashboard.
2. Go to Workers & Pages → Create → Pages.
3. Connect the GitHub repository `rubayatshakil4-hash/safwan-wifi-isp`.
4. Select the `main` branch.
5. Framework preset: None.
6. Build command: leave empty.
7. Build output directory: `/`.
8. Deploy.

After the first deploy, add a custom domain in the Pages project settings if you own one.

## Next development stages
1. Confirm business contact details and service area.
2. Build Cloudflare Worker API and D1 database.
3. Add secure customer login and voucher workflows.
4. Add admin roles, POS, reports and payment records.
5. Integrate Omada Controller through a server-side Worker. Keep controller passwords, tokens and API secrets in Cloudflare secrets; never put them in browser JavaScript or public repository files.
