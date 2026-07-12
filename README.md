# Lillip Apps

`Lillip Apps` is a lightweight static app catalog for Show1005's small, single-purpose iPhone apps.

The site is intended to be the public-facing hub for app discovery, App Store links, and cross-app navigation.

## Concept

小さく、すぐ使えるiPhoneアプリ集。

## Repository purpose

This repository hosts the app introduction site.

It is responsible for:

- Showing available and upcoming apps
- Explaining each app in one short sentence
- Linking to App Store pages
- Linking to Privacy Policy and Support pages hosted elsewhere
- Creating a cleaner public hub than `app-legal-pages`

## Relationship with app-legal-pages

`lillip-apps` and `app-legal-pages` have separate roles.

### lillip-apps

- アプリ紹介
- ブランドサイト
- App Store導線
- アプリ間回遊

### app-legal-pages

- Privacy Policy
- Support
- 補助ツール
- App Store Connect用URL

`app-legal-pages` should remain the stable legal/support URL host. This site links to it, but does not move or duplicate legal page content.

## Site structure

```text
index.html
assets/
  icons/
  screenshots/
docs/
  site-role.md
```

## Publishing

This site is designed for GitHub Pages.

No build step is required. The site can be served directly from the repository root.

## Technical policy

- Plain HTML / CSS
- No external libraries
- No React / Next.js / Vite
- No build tool
- No tracking or analytics by default
- No server-side processing

## Link maintenance

Some apps may not have confirmed URLs yet.

Use `#` only as a temporary placeholder for:

- App Store URL
- Privacy Policy URL
- Support URL
- Tool URL

Do not invent or guess URLs. Replace placeholders only after the target page exists.

## Current follow-up items

- Replace placeholder links for unreleased apps
- Add real app icons under `assets/icons/`
- Add screenshots if needed under `assets/screenshots/`
- Update `app-legal-pages` top page to link back to Lillip Apps
