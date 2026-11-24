# Deutsch Meister — starter website

This is a static website starter for Deutsch Meister. It can be published free on Cloudflare Pages using the `*.pages.dev` address.

## Files
- `index.html` — page structure
- `styles.css` — responsive styling
- `app.js` — learning content and browser-side interactions

## Publish free with Cloudflare Pages (no coding required)
1. Create a free account at https://dash.cloudflare.com/
2. Create a GitHub account at https://github.com/ if you do not already have one.
3. On GitHub, create a new **public** repository named `deutsch-meister`.
4. Upload `index.html`, `styles.css`, and `app.js` from this folder to the repository's main/root directory.
5. In Cloudflare, open **Workers & Pages** → **Create** → **Pages** → **Connect to Git**.
6. Select your GitHub account and the `deutsch-meister` repository.
7. For a plain HTML site, choose **None** as the framework preset. Leave the build command blank. Set the build output directory to `/` (or `.` if the interface asks for a relative path).
8. Click **Save and Deploy**. Cloudflare will provide a public address such as `https://deutsch-meister.pages.dev`.

If the deployment screen differs, follow Cloudflare's current Pages instructions: https://developers.cloudflare.com/pages/get-started/git-integration/

## Important before public launch
- This version is a working starter, not the complete A1–B2 course. The vocabulary and tests are sample content.
- Progress is saved only in the current browser/device using localStorage. Clearing browser data can erase it.
- No user login, cloud database, AI sentence correction, full listening library, or full weekly exam system is connected yet.
- Do not put private API keys in `app.js` or any browser-side file. Any AI feature must call a secure server-side function.
- Review German examples and translations before using this as a formal teaching resource.

## Recommended next development stages
1. Expand and proofread the CEFR A1 curriculum.
2. Add a proper question bank and spaced-repetition scheduling.
3. Add secure accounts and cloud progress (for example, Supabase).
4. Add AI sentence feedback through a server-side endpoint.
5. Add audio recordings and structured listening/speaking activities.
6. Build B2 and healthcare modules with reviewed content.
