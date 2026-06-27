# KitchenPro Store Publishing Notes

## What Was Added

- Mobile-style intro screen.
- New KitchenPro logo style.
- Colorful professional app theme.
- Dropdown question type in the form builder.
- Existing backup and Excel export tools are still included.

## Important Store Requirement

Google Play Store and Apple App Store do not publish a plain HTML file directly. The app needs to be wrapped as a real mobile app package:

- Android: APK or AAB file.
- iPhone: iOS app uploaded through Xcode / Apple Developer.

## Recommended Path

Use Capacitor to wrap this HTML app:

1. Create a small Capacitor project.
2. Put `kitchen-checklist-admin.html` and assets inside the web folder.
3. Configure app name: `KitchenPro`.
4. Use `kitchenpro-logo.svg` to generate Android and iOS icons.
5. Connect a shared database before public team launch.
6. Build Android AAB for Google Play.
7. Build iOS app archive for App Store.

## Database Before Publishing

For a professional team app, do not rely only on browser storage. Choose one:

- Firebase under your Google account for live shared team data.
- Google Sheets plus Apps Script for simple Google-account storage.
- Supabase or another hosted database.

## Store Listing Basics

Suggested app name: KitchenPro Checklist

Short description:
Professional kitchen checklist, photo proof, team submissions, and Excel reports.

Categories:
Business, Productivity, Food & Drink

Privacy note:
The app may store employee names, checklist answers, photos, and submission history. Add a privacy policy before publishing.

