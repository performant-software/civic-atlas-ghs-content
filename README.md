# Civic Atlas — Georgetown HS

Content repository for the Civic Atlas pilot at Georgetown High School (Massachusetts).

This is a Core Data Places site. The codebase lives at [performant-software/core-data-places](https://github.com/performant-software/core-data-places); this repository holds the site's branding, configuration, navigation, and editorial content.

## What's here

- `content/settings/config.json` — site config (search indexes, layers, FairData project)
- `content/branding/branding.json` — logo and footer
- `content/i18n/en.json` — UI string translations
- `content/navbar/en.json` — top navigation
- `content/pages/` — TinaCMS-managed static pages
- `content/posts/` — blog posts (created via TinaCMS admin)
- `content/paths/` — curated narrative tours through places
- `content/users/index.json` — fallback admin user (overridden by Clerk SSO)

## Deployment

The site is built from this repo by Netlify. Editors save changes via the TinaCMS admin, which commits back to `main` here through the GitHub API.
