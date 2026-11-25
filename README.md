# Thudzamendes Fitness – Membership & Payments

A simple, private web tool for tracking gym members and monthly payments.

## Features
- Enrol members (name, phone, plan, monthly fee)
- Monthly view of who has paid and who has not
- Mark paid / undo, search, filter by Paid or Unpaid
- Copy the list of unpaid members for reminders
- Download a backup (JSON) and restore from a backup

## Using the app
1. Open the site and enrol members.
2. Record payments each month with **Mark paid**.
3. Download a backup regularly with **Download backup** and keep it safe.
4. To move to another computer, open the site there and use **Restore backup**.

Data is stored in the browser on the device you use. Use backups to avoid losing data.

## Publishing on GitHub Pages
1. Create a new repository on GitHub, for example `thudzamendes-fitness`.
2. Upload `index.html` and `README.md` (or push this folder with git).
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. After a minute the site is live at `https://<your-username>.github.io/thudzamendes-fitness/`.

## Notes
- The page loads fonts from Google Fonts; it needs an internet connection for the first load.
- Keep the repository **private** if you want the site hidden. GitHub Pages on a private repo needs a paid GitHub plan; on a free plan the site must be public.
