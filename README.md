# Strength Foundations — 3-Day Split

A single-page site for a beginner strength program built around the compound
lifts (squat, deadlift, overhead press). Anterior / Posterior / Shoulders split,
double-progression rep scheme, coach notes. Fully responsive, no build step,
no dependencies.

## Put it online with GitHub Pages

1. Create a new repository on GitHub (e.g. `strength-foundations`).
2. Upload `index.html` (and this `README.md`) to the repo — either drag them
   into the "Add file → Upload files" screen, or push from your machine:

   ```bash
   git init
   git add index.html README.md
   git commit -m "Add workout split site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/strength-foundations.git
   git push -u origin main
   ```

3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set the branch to **main** and the folder to **/ (root)**, then **Save**.
6. Wait ~1 minute. Your site goes live at:

   ```
   https://YOUR-USERNAME.github.io/strength-foundations/
   ```

That's it — `index.html` at the repo root is all GitHub Pages needs.

## Editing

Everything (HTML, CSS, JS) lives in `index.html`. To swap an exercise, edit the
matching `.row`. Main lifts use `class="row main"`; tags are `Main lift`,
`Accessory`, or `Core`.
