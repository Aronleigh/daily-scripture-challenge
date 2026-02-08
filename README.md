# Daily Scripture Challenge (Set-and-Forget)

This is a tiny single-page website that shows:
- Today's Scripture reference (and tries to fetch KJV verse text)
- A small daily challenge
- A reflection question

## How it works
- The site picks a day entry based on your local date (day-of-year).
- It uses the embedded 365-day plan.
- It *tries* to fetch KJV verse text from https://bible-api.com (if it fails, it still shows the reference).

## Publish (GitHub Pages)
1. Create a GitHub account.
2. Create a new public repo named `daily-scripture-challenge`.
3. Upload `index.html`.
4. Repo Settings → Pages → Deploy from `main` branch, folder `/ (root)` → Save.
5. Your live site URL will be: https://YOUR-USERNAME.github.io/daily-scripture-challenge/

## Edit later
Edit `index.html` in GitHub and commit changes. Your site updates automatically.
