# My Life — build your own Android app (free)

You do 3 things. GitHub's computers do the rest.

## Step 1 — Create a free GitHub account (once)
Go to github.com on a computer, sign up (free).

## Step 2 — Upload this folder (once)
1. On GitHub, click the "+" (top right) -> "New repository"
2. Name it: my-life-app  ->  click "Create repository"
3. Click "uploading an existing file"
4. Open this unzipped folder on your computer, select EVERYTHING inside it
   (www, resources, .github, package.json, capacitor.config.json, README.md)
   and drag it all into the GitHub page.
   IMPORTANT: upload the CONTENTS of the folder, not the folder itself.
   NOTE: the ".github" folder may be hidden - press Ctrl+H (Linux) or
   enable View -> Show hidden files (Windows) to see it.
5. Click "Commit changes"

The build starts by itself. Wait ~10 minutes.

## Step 3 — Download your app
1. On your repository page, click the "Actions" tab
2. Click the run at the top (green tick = finished)
3. Scroll down to "Artifacts" -> click "My-Life-app" to download a zip
4. Send that zip to your phone (WhatsApp to yourself works), unzip,
   tap app-debug.apk to install
5. Android will warn "unknown developer" - normal for personal apps.
   Tap "Install anyway".

Done. The compass icon appears in your app drawer.

## Updating the app later
Replace www/index.html with a newer version (Upload files again on GitHub),
commit, wait 10 minutes, download the new APK, install over the old one.
Your data is kept.

## First run
When you first tap "Start 25m", Android asks permission to send
notifications - tap Allow, so the timer can ring even when the app
is closed.
