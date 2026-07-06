# Ministry Expense Tracker — Setup Guide

Your app is two files: `index.html` and `geo.js` (the country/state lists). To use it on your iPhone, they need to be on the web (free, ~10 minutes, one time).

## Step 1: Put it online (free, one time)

**Option A — GitHub Pages (recommended, permanent):**
1. Create a free account at github.com
2. Click **+** → **New repository**, name it `expense-tracker`, set it to **Public**, click Create
3. Click **uploading an existing file**, drag in `index.html` **and** `geo.js`, click **Commit changes**
4. Go to **Settings → Pages**, under "Branch" choose `main`, click **Save**
5. After ~1 minute your app is live at `https://YOURUSERNAME.github.io/expense-tracker/`

**Option B — Netlify:** free account at netlify.com → drag the folder onto the Drop zone → get a URL.

## Step 2: Install on your iPhone

1. Open the URL in **Safari** on your iPhone
2. Tap the **Share** button → **Add to Home Screen** → **Add**
3. It now opens full-screen from your home screen like a regular app

## Step 3: First-use permissions

- **Camera/Photos:** tapping the receipt photo field asks once — allow it
- **Location:** tapping Start Trip asks — choose **Allow While Using App** and make sure Precise Location is on (Settings → Privacy → Location Services → Safari Websites)

## Using it

**Receipts:** tap the photo field (opens camera), fill in date/amount/category/vendor/purpose, Save. Tap any saved receipt to view, share its photo, or delete it.

**Mileage:** name the trip, enter start odometer (auto-filled from your last trip), tap **Start**, drive, tap **Stop** on arrival. GPS distance and end odometer are calculated; adjust if needed, then Save.

**Export:** pick a date range (optional), then export the mileage log or receipt list as Excel, or share all receipt photos at once. Use the share sheet to **Save to Files → iCloud Drive** or email directly for reimbursement.

## Important notes

- **Keep the app open while driving.** iPhones pause web apps in the background, so GPS only tracks with the app on screen. The app keeps your screen awake automatically — a dash mount and car charger work well. If the app is interrupted mid-trip, reopen it and tap "Resume trip"; miles already driven are kept.
- **Backups:** receipts and trips are stored on your phone (in Safari's storage for this site). Export to Excel/iCloud regularly — and don't clear Safari website data for this site, or use "Erase All Content", without exporting first.
- **iCloud:** exports saved via **Save to Files → iCloud Drive** sync to iCloud automatically. Receipt photos taken with the Camera through the app can also be shared to Photos (which backs up to iCloud Photos).
- GPS distance is typically within 1–2% of your odometer and is accepted for IRS mileage logs; you can hand-correct the end odometer on the finish screen any time.
