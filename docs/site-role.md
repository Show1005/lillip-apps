# Site Role

## Purpose

`lillip-apps` is the public-facing app catalog and brand site for Show1005's small, single-purpose iPhone apps.

`app-legal-pages` remains the supporting repository for legal, support, and helper-tool pages used by App Store Connect and individual apps.

## lillip-apps

Role:

- アプリ紹介
- ブランドサイト
- App Store導線
- アプリ間回遊

This site should answer:

- What apps exist?
- What is each app for?
- Where can users download each app?
- Where can users find support, privacy policy, or helper tools?

This site should not become a legal page repository.

## app-legal-pages

Role:

- Privacy Policy
- Support
- 補助ツール
- App Store Connect用URL

This repository should continue to host stable URLs for App Store Connect, support pages, privacy policies, and helper tools such as share viewers or app-specific utilities.

## Link policy

`lillip-apps` should link to `app-legal-pages` for:

- Privacy Policy
- Support
- App-specific helper tools

`app-legal-pages` should link back to `lillip-apps` from its top page so users who land on a legal/support page can discover the app catalog.

## Follow-up items for app-legal-pages

- app-legal-pages のトップから Lillip Apps へリンクする
- app-legal-pages は法務・サポート置き場であることを明示する
- 各アプリの Privacy / Support URL を整理する
- Lillip Apps 側から参照するURL一覧を後で確定する

## Out of scope for this repository

- Privacy Policy body text
- Support FAQ body text
- App Store Connect legal URL hosting
- Helper tools that belong to a specific app legal/support flow
- Analytics or tracking scripts
- Server-side processing
