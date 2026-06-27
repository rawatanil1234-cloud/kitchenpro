# Kitchen Checklist Team Launch Guide

## What You Have Now

You have a working offline checklist app:

- App file: `kitchen-checklist-admin.html`
- Admin can create users, build checklists, collect submissions, export Excel, and make backups.
- Data is saved in the browser where the app is opened.

Important: if each employee opens their own copy, their data stays on their own phone/browser. For one shared team database, the app must be connected to an online database such as Firebase, Google Sheets with Apps Script, or another server.

## Fast Launch Today

Use this if you want to start with the team immediately.

1. Open `kitchen-checklist-admin.html`.
2. Sign in with the initial admin login:
   - Username: `admin`
   - Password: `admin123`
3. Go to Users and create employee accounts.
4. Go to Checklists and create the checklists your team must fill.
5. Go to Backup & Export.
6. Download an Android/iPhone file if you want to send the app to phones.
7. Download a Full database backup at the end of every day.
8. Download Excel anytime for reports.

Recommended pilot setup: use one admin tablet, laptop, or shared phone as the main device until an online database is connected.

## Before You Share With The Team

Do these first:

- Change the admin password by editing the admin user in Users.
- Add only real team users.
- Create your final checklists.
- Test one employee submission.
- Export Excel once and confirm the report opens correctly.
- Download a database backup and save it in Gmail or Google Drive.

## How To Share On Android

1. Open the app as admin.
2. Go to Backup & Export.
3. Click Android download.
4. Send the downloaded HTML file to the phone by WhatsApp, Gmail, or Drive.
5. Open it in Chrome.

Note: the phone will have its own local data unless you import the shared backup file.

## How To Share On iPhone

1. Open the app as admin.
2. Go to Backup & Export.
3. Click iPhone download.
4. Send the downloaded HTML file to the iPhone by Gmail, Drive, or AirDrop.
5. Open it in Safari or Files.

Note: iPhone storage is also separate unless you import a backup file.

## Gmail / Google Drive Backup

The app cannot silently save inside Gmail by itself. Gmail is email, not a database.

Use this workflow:

1. Go to Backup & Export.
2. Click Download backup.
3. Save the JSON backup file in Gmail or Google Drive.
4. To restore later, open the app and use Import backup.

## Real Team Launch With Shared Data

For a proper team launch where everyone submits from their own phone and admin sees everything live, choose one database option:

- Firebase with your Google account: best for live shared app data.
- Google Sheets plus Apps Script: simple and Google-account friendly, but slower and more limited.
- Supabase or another hosted database: strong option if you already use it.

What is needed next:

1. A hosting location for the app.
2. A shared database.
3. Login and permissions connected to that database.
4. Backup/export still kept in the admin page.

## Launch Day Checklist

- Admin password changed.
- All staff users created.
- Checklists tested.
- Backup downloaded.
- Excel export tested.
- Team told which device/link to use.
- One person assigned to download daily backup.

