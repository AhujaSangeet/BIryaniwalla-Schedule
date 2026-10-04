# Biryaniwalla Staff Schedule - GitHub Pages setup

Files: `index.html` (the page) and `schedule.json` (the schedule data - this is the file that changes each week).

## One-time setup
1. On github.com create a new repository (e.g. `biryaniwalla-schedule`).
2. Upload `index.html` and `schedule.json` to the repository root.
3. Settings > Pages > "Deploy from a branch" > `main` / `(root)` > Save.
   Your site will be at `https://<your-username>.github.io/biryaniwalla-schedule/`.
4. Create a token so the Manager portal can publish: GitHub > Settings > Developer settings >
   Personal access tokens > Fine-grained tokens > Generate new token.
   Repository access: only your schedule repo. Permissions: Contents = Read and write.

## Every week
1. Open the site, scroll to the bottom and tap **Manager**.
2. First time only: tap **GitHub settings**, enter `your-username/biryaniwalla-schedule`, branch `main`, paste the token.
3. Edit shifts, then tap **Publish to GitHub**. The live page updates in about a minute.
   (No token? Tap **Download JSON** and upload it to the repo, replacing `schedule.json`.)

## Notes
- The token is stored only in the browser you paste it into. Never put it in the repo.
- Anyone can open Manager and edit their own view, but only someone with the token can publish.
- If the repo is public, the schedule (staff names and shifts) is publicly readable.
- **Save image** on the main page creates a PNG of the whole week (shares directly on phones/iPad).
