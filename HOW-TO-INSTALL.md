# Flan: install on your iPhone

## Part 1: put the app online (once, ~10 min, on your laptop)
1. Go to github.com and create a free account.
2. Click the **+** at the top right > **New repository**. Name it `flan`. Keep it **Public**. Click **Create repository**.
3. Click **uploading an existing file**. Drag in these 7 files: `index.html`, `manifest.webmanifest`, `sw.js`, `apple-touch-icon.png`, `icon-192.png`, `icon-512.png`, `HOW-TO-INSTALL.md`. Click **Commit changes**.
   - Do NOT upload `flan-my-setup.json` or any backup file. Those hold your numbers.
4. In the repo, click **Settings** > **Pages** (left menu). Under "Branch", pick **main** and **/(root)**, then **Save**.
5. Wait 1 to 2 minutes and refresh. Your link appears at the top: `https://YOURNAME.github.io/flan/`.

## Part 2: install it on your iPhone
1. Open that link in **Safari** (not Chrome).
2. Tap **Share** (square with arrow) > **Add to Home Screen** > **Add**.
3. Open Flan from your home screen. From now on, always open it from the icon.

## Part 3: load your plan (once)
1. Save `flan-my-setup.json` to your iPhone's **Files** app (iCloud Drive is fine).
2. In Flan, tap the gear > **Import** > pick `flan-my-setup.json`.
3. Flan greets you by name. Done.

## Backups
Your data lives only on your phone. Once a month: gear > **Export**, save the file to iCloud Drive.

## Updating the app later
Upload the new `index.html` to the same GitHub repo. Close and reopen Flan twice to get it.
