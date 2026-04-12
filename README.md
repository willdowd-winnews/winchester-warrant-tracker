# Winchester Warrant Tracker

This package is prepared as a simple GitHub Pages website. It is designed so you can upload it to a brand-new GitHub repository without needing GitHub Desktop, the command line, or any coding setup.

The site is a single-page, static tracker for Winchester's 2026 Spring Annual Representative Town Meeting warrant. Everything needed to run the page is already inside `index.html`, including styling and interactive filtering.

## Suggested Repository Setup

Repository name:
`winchester-warrant-tracker`

Suggested short description:
`Interactive tracker for Winchester's 2026 Spring Annual Representative Town Meeting warrant articles.`

Suggested longer description for notes, documentation, or the About box:
`A public, static GitHub Pages site presenting all 46 warrant articles for Winchester's 2026 Spring Annual Representative Town Meeting in a searchable, filterable tracker. The page is designed for readers to quickly scan article titles, categories, vote thresholds, committee recommendations, and outcomes in one place.`

## Files In This Folder

- `index.html`
  This is the website itself. GitHub Pages will use this file as the homepage.

- `README.md`
  This file explains how to upload and publish the tracker.

## What This Package Is For

Use this folder when you want to:

- create a brand-new repository on a different GitHub account
- upload the tracker manually through the browser
- publish it as a GitHub Pages website
- avoid command line setup

## Step-By-Step Upload Instructions

### 1. Open your browser

Go to [https://github.com](https://github.com).

### 2. Sign in to the GitHub account you want to use

Make sure you are signed into the correct GitHub account for this tracker. This should be the other account, not the one used for the Marblehead newsletter archive.

### 3. Create a new repository

In the upper-right corner of GitHub:

1. Click the `+` icon.
2. Click `New repository`.

### 4. Fill out the repository details

Use these settings:

- Repository name: `winchester-warrant-tracker`
- Description: `Interactive tracker for Winchester's 2026 Spring Annual Representative Town Meeting warrant articles.`
- Visibility: `Public`

Do not check:

- `Add a README file`
- `Add .gitignore`
- `Choose a license`

Then click `Create repository`.

### 5. Upload the files manually

After the repository is created, GitHub will show a page with several setup options.

1. Click `uploading an existing file`.
2. Open this folder on your computer.
3. Drag `index.html` into the GitHub upload area.
4. Drag `README.md` into the same upload area if you want the repository to include publishing notes.

Important:

- `index.html` must be uploaded.
- The page will not work as a GitHub Pages homepage unless `index.html` is present in the repository root.

### 6. Commit the uploaded files

Scroll to the bottom of the upload screen.

Use a commit message like:

`Add Winchester warrant tracker site`

Then click `Commit changes`.

### 7. Turn on GitHub Pages

Once the files are in the repository:

1. Click `Settings` near the top of the repository.
2. In the left sidebar, click `Pages`.
3. Find the `Build and deployment` section.
4. Under `Source`, choose `Deploy from a branch`.
5. Under `Branch`, select `main`.
6. Under folder, select `/ (root)`.
7. Click `Save`.

### 8. Wait for publishing

GitHub Pages usually takes a minute or two to publish the site.

After it finishes, GitHub will show the public site URL in the Pages settings area.

The address will usually look like:

`https://YOUR-USERNAME.github.io/winchester-warrant-tracker/`

### 9. Open the live site

Click the published URL once GitHub shows it.

Check that:

- the page loads
- the filters work
- the article list appears
- the layout looks correct on desktop and mobile

## Optional: Add the Repository Description After Upload

After the repository is live, you can also add or update the repository description on the main repository page.

Suggested text:

`Interactive tracker for Winchester's 2026 Spring Annual Representative Town Meeting warrant articles.`

## Optional: If You Want a Simpler Public URL

If you want the site to appear at the root of the account's GitHub Pages domain instead of under a repository path, the repository must be named:

`YOUR-USERNAME.github.io`

That is only necessary if you want a root site URL. For most cases, `winchester-warrant-tracker` is the better and simpler choice.

## Troubleshooting

### The Pages site does not appear right away

Wait 1 to 5 minutes, then refresh the Pages settings screen.

### The page is blank

Make sure `index.html` is in the top level of the repository, not inside another folder.

### The URL gives a 404 error

GitHub Pages may still be building. Wait a few minutes and try again.

### The wrong account is showing

Log out of GitHub and log back into the correct account before creating the repository.

## Summary

You are uploading a ready-made static site. No build step, framework, or extra assets are required. As long as `index.html` is uploaded to the repository root and GitHub Pages is turned on for the `main` branch, the tracker should publish correctly.
