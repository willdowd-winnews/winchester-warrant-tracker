# Winchester Warrant Tracker

An interactive, single-page tracker for all 46 warrant articles at Winchester's 2026 Spring Annual Representative Town Meeting. Everything needed to run the page — styling, data and interactive filtering — lives inside `index.html`.

## Current features

- Searchable, filterable table of all 46 warrant articles
- Category, stakes and keyword filters
- Expandable article details with sponsor, dollar amounts and context
- Color-coded badges for Select Board and FinCom recommendations and Town Meeting results
- Sticky black column header bar that follows the reader while scrolling
- Horizontal badge scrolling on mobile (no stacking)
- Responsive layouts for desktop, tablet, phone portrait and phone landscape
- Landscape-optimized mobile note for readers
- Touch-friendly tap targets on mobile devices
- Print stylesheet

## Files in this folder

- `index.html` — The full standalone website. GitHub Pages will use this file as the homepage.
- `README.md` — This file.

## Repository setup

Repository name: `winchester-warrant-tracker`

Short description: `Interactive tracker for Winchester's 2026 Spring Annual Representative Town Meeting warrant articles.`

## Step-by-step upload instructions

### 1. Create a new repository

Go to [https://github.com](https://github.com) and sign in to the correct account.

Click the `+` icon in the upper right, then click `New repository`.

Use these settings:

- Repository name: `winchester-warrant-tracker`
- Description: `Interactive tracker for Winchester's 2026 Spring Annual Representative Town Meeting warrant articles.`
- Visibility: `Public`

Do not check `Add a README file`, `Add .gitignore` or `Choose a license`.

Click `Create repository`.

### 2. Upload the files

After the repository is created:

1. Click `uploading an existing file`.
2. Open this folder on your computer.
3. Drag `index.html` into the upload area. This file is required.
4. Optionally drag `README.md` into the same area.

Scroll down and commit with a message like `Add Winchester warrant tracker site`.

### 3. Turn on GitHub Pages

1. Go to `Settings` > `Pages`.
2. Under `Source`, choose `Deploy from a branch`.
3. Under `Branch`, select `main` and `/ (root)`.
4. Click `Save`.

Publishing usually takes one to two minutes. The live URL will appear in the Pages settings and will look like:

`https://YOUR-USERNAME.github.io/winchester-warrant-tracker/`

### 4. Verify

Check that the page loads, the filters work, the article list appears and the layout looks correct on desktop and mobile.

## Troubleshooting

**The page is blank.** Make sure `index.html` is in the top level of the repository, not inside another folder.

**The URL gives a 404 error.** GitHub Pages may still be building. Wait a few minutes and try again.

**The wrong account is showing.** Log out and log back into the correct account before creating the repository.

## Summary

This is a ready-made static site. No build step, framework or extra assets are required. Upload `index.html` to the repository root, turn on GitHub Pages for the `main` branch and the tracker will publish.
