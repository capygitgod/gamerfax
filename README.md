# Pixelpedia

A responsive gaming and technology discovery directory with cyan-accented styling.

## Explore
- Game genres, individual game pages and game creators with generated artwork where no official cover is available
- Gaming gear and PC components with product photos where available and consistent fallback artwork
- Technology creators and their channels, with profile photos or generated monogram thumbnails
- A sourced news feed for gaming, technology and Pixelpedia updates
- Brand, platform and gaming abbreviation directories
- PC-building resources including PCPartPicker and Logical Increments

## Accounts and management
- Public browsing
- Email-verified user accounts with customizable profiles and avatars
- Email-verified password reset/change flow
- Saved games, gear and PC parts stored in the visitor's browser
- Signed-in community suggestions
- Private, owner-only content management
- Owner-only notification centre
- News publication controls and creator-directory editing
- Manually curated, source-linked news rather than an automatic scraper

## Run locally
Open `index.html` in a browser. The site uses Supabase for its catalogue and account features.

## Cloudflare Workers
This repository is a static HTML site. Cloudflare Workers Builds can connect the repository to a Worker and deploy changes from the selected Git branch. Review any Wrangler configuration pull request Cloudflare generates and make sure its Worker name matches the Worker created in the dashboard.

Keep public client configuration separate from private credentials. Never commit passwords, service-role keys, API tokens or other secrets to this repository.
