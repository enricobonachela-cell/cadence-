# Cadence

Your own habit tracker: habits with streaks, tasks, a focus timer, mood check-ins and stats.
Everything is stored on your phone. Nothing is sent anywhere.

## Put it on your iPhone (free, ~5 minutes)

The app needs to live at a web address once, so Safari can install it. GitHub Pages is free:

1. Create a free account at github.com and make a new **public** repository called `cadence`.
2. On the repo page, choose **Add file → Upload files** and drag in everything from this folder
   (all 9 files; there are no subfolders). Commit.
3. Go to **Settings → Pages**, set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. After a minute your app is at `https://<your-username>.github.io/cadence/`.
5. Open that address in **Safari** on your iPhone → Share → **Add to Home Screen** → Add.
6. Open Cadence from the icon. From now on it works offline.

## Keep your data safe

- Data is saved inside the installed app. Deleting the home-screen icon deletes the data.
- Use Settings → Backup → Download now and then. Restore from the same screen.

## Updating the app

Upload the new index.html to the repo. The next time you open Cadence with internet, it picks up
the new version (close and reopen it once more to see it).
When you change files, bump `VERSION` in sw.js so old caches are cleared.
