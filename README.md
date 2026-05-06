# Design Project Tracker

Live pipeline report for interior design projects, built from Asana portfolio data.

## Files

- `index.html` — the full report (self-contained, no dependencies)
- `vercel.json` — Vercel deployment config

## How to deploy

### Step 1 — GitHub

1. Go to [github.com](https://github.com) and sign in (or create a free account)
2. Click **+** → **New repository**
3. Name it `design-tracker` (or anything you like), set it to **Private**, click **Create repository**
4. On the next screen click **uploading an existing file**
5. Drag and drop both `index.html` and `vercel.json` into the upload area
6. Click **Commit changes**

### Step 2 — Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with your GitHub account
2. Click **Add New → Project**
3. Find and click **Import** next to your `design-tracker` repository
4. Leave all settings as default — click **Deploy**
5. In ~30 seconds you'll get a live URL like `https://design-tracker-xyz.vercel.app`

That's it — send that URL to your boss!

## Keeping it up to date

The data is a snapshot. To refresh:
1. Ask Claude to regenerate the report with updated Asana data
2. Download the new `index.html`
3. Go to your GitHub repo → click `index.html` → click the pencil (edit) icon → paste the new content → commit
4. Vercel auto-redeploys in ~20 seconds
