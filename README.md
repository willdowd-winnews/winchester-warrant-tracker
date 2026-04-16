# Winchester Warrant Tracker

An interactive, single-page tracker for all 46 warrant articles at Winchester's 2026 Spring Annual Representative Town Meeting. Everything needed to run the page lives inside `index.html`, including the styling, article data and front-end filtering logic.

## Current features

- Searchable, filterable table of all 46 warrant articles
- Category, stakes and keyword filters
- Expandable article details with sponsor, dollar amounts and context
- Color-coded badges for Select Board and Finance Committee recommendations and Town Meeting results
- Sticky black column header bar that follows the reader while scrolling
- Horizontal badge scrolling on mobile
- Responsive layouts for desktop, tablet, phone portrait and phone landscape
- Landscape-optimized mobile note for readers
- Touch-friendly tap targets on mobile devices
- Print stylesheet

## Files in this repository

- `index.html` - The full standalone website. GitHub Pages uses this file as the homepage.
- `README.md` - This file.

## Repository

- GitHub repo: `https://github.com/willdowd-winnews/winchester-warrant-tracker`
- Local working copy: `C:\WinDocs_All\WinDocs\winchester-warrant-tracker`

## How this project works now

This repository is already connected to GitHub. The tracker should be edited in the local repo folder above, not in a separate scratch folder.

The normal workflow is:

1. Open `C:\WinDocs_All\WinDocs\winchester-warrant-tracker` as the active Codex project.
2. Make changes to `index.html` and `README.md` in that repo.
3. Preview `index.html` locally in a browser.
4. Commit and push the updates to GitHub.

## Edit and publish workflow

### 1. Go to the repo folder

```powershell
cd C:\WinDocs_All\WinDocs\winchester-warrant-tracker
```

### 2. Check the repo state

```powershell
git status
```

### 3. After making changes, stage the files

```powershell
git add .
```

### 4. Commit the update

```powershell
git commit -m "Describe the tracker update"
```

Example:

```powershell
git commit -m "Update Select Board recommendations"
```

### 5. Push to GitHub

```powershell
git push
```

## Local preview

To preview the tracker before pushing changes, open `index.html` directly in your browser from the repo folder.

## GitHub Pages

GitHub Pages should publish from the `main` branch at the repository root.

If you ever need to verify the setting:

1. Open the repository on GitHub.
2. Go to `Settings` > `Pages`.
3. Under `Source`, choose `Deploy from a branch`.
4. Set `Branch` to `main` and the folder to `/ (root)`.

## Troubleshooting

**The page is blank.** Make sure `index.html` is still in the top level of the repository.

**The site does not show the latest changes.** Wait a minute or two after `git push`, then hard refresh the browser.

**Git says there is nothing to commit.** Run `git status` and make sure you edited files inside `C:\WinDocs_All\WinDocs\winchester-warrant-tracker`, not in another folder.

**Changes were made in the wrong folder.** Copy the updated files into the repo folder, then run `git add .`, `git commit` and `git push`.

## Summary

This is a ready-made static site with no build step, framework or extra assets required. Edit the files in the local GitHub-connected repo, preview `index.html`, then use `git add .`, `git commit` and `git push` to publish updates.
