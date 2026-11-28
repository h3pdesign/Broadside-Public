# Broadside — public website

Standalone GitHub Pages marketing site for Broadside, modeled on the Morphia and Liquid Record public websites. This repository contains only public website content and selected App Store screenshots, not the app source.

Live site: https://h3pdesign.github.io/Broadside-Public/ (English) and https://h3pdesign.github.io/Broadside-Public/de/ (German)

## Hosting

GitHub Pages serves the `main` branch root. `.nojekyll` enables direct static serving. There are no JavaScript dependencies, trackers, cookies, external fonts, or third-party embeds.

## Preview

Run `python3 -m http.server 8080` in this folder, then open http://localhost:8080.

## App Store release

Broadside is not on the App Store yet (App Store name "Broadside Newspaper", app id 6839681018). Since November 28, 2026 the primary buttons link to the public TestFlight beta, https://testflight.apple.com/join/rrdjZYj8. On release, add `<meta name="apple-itunes-app" content="app-id=6839681018">`, change the status line, and point the primary buttons to https://apps.apple.com/app/id6839681018 on both pages.

Pricing (€4.99 per month, €19.99 per year, €39.99 Lifetime in Germany, 7-day free trial on the subscriptions) comes from the app's StoreKit configuration and App Store metadata as of November 27, 2026. Verify against the live listing after release. Local prices may vary. English and German pages must stay in sync.

Screenshots are the raw app captures of version 1.0 composed into real Apple device bezels (Apple Design Resources: iPhone 18 Pro Max, iPad Pro 13", MacBook Pro 16") with transparent backgrounds, in `assets/screenshots/devices` (iPhone 700 px, iPad 1000 px, Mac 1600 px wide, WebP with alpha). They have no baked-in captions, so both languages share them and captions live in the HTML.

## Rights

Copyright © 2026 h3p. App branding, screenshots, and website content are reserved to their owner. Public availability does not grant a license to redistribute the app or its assets.
