# Temple Guard Database — Version 1.0

A static, dark-red command dashboard prototype for GitHub Pages.

## Features
- Dashboard with member and activity counts
- Searchable member database and member profiles
- Rank hierarchy and leadership directory
- Promotion/demotion logs and activity records
- Local demo admin tools: add/edit/delete members, record activity, export/import JSON
- Mobile-friendly design

## IMPORTANT: Security and privacy
**This is NOT a private website or secure admin system.** GitHub Pages websites are publicly accessible, even if their repositories are private. The Admin Dashboard has no authentication. Its changes are saved in browser localStorage only, not to a shared server. Do not use this prototype for confidential member data, private personnel records, or passwords.

For a truly private system, use an authentication provider, a server-side authorization layer, a real database with row-level access controls, and a hosting solution that enforces access before serving sensitive content. Do not store private records in public static HTML, JavaScript, JSON, or the repository.

## Publish on GitHub Pages
1. Create a GitHub account at https://github.com if needed.
2. Create a new **public** repository named `temple-guard-database`.
3. Upload `index.html`, `styles.css`, and `app.js` to the root of the repository. `README.md` is optional.
4. Go to **Settings → Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**. Choose `main` and `/ (root)` and save.
6. Once deployed, visit `https://YOUR-USERNAME.github.io/temple-guard-database/`.

If instead you name the repository `YOUR-USERNAME.github.io`, the site will be at `https://YOUR-USERNAME.github.io/`.

## Customize
- Edit `styles.css` to change colors and layout.
- Edit `app.js` to customize the rank list or fictional sample data.
- To reset local edits, open Admin Dashboard → Reset Demo.
- The site does not synchronize edits across devices or users.
