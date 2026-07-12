# ConvEx Agent Handbook

Internal knowledge base for FC Sales agents. Built and maintained by ConvEx.

## Deploy to Vercel

1. Push this repo to GitHub
2. Go to [vercel.com](https://vercel.com) → New Project → Import this repo
3. Framework Preset: **Other**
4. Output Directory: **public**
5. Click Deploy

## Manager Mode

Click the 🔒 Manager button in the top bar. Default password: `convex2026`

Change the password by editing the `MGR_PW` variable in `public/index.html`.

## Editing Content

1. Enable Manager Mode (password required)
2. Click ✏️ on any card to edit, or click "+ Add New Page"
3. Changes save to the browser's localStorage automatically
4. To make permanent changes, edit the DEFAULT_PAGES array in index.html

## Structure

```
public/
  index.html    ← The entire app (single file, no build step)
vercel.json     ← Vercel config
package.json    ← Project metadata
```
