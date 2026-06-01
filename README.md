# FinanceOS — Landing Page

A single-file, dependency-free landing page for the FinanceOS app, with 3D
tilt/parallax effects, glassmorphism, and the app's violet/indigo branding.

## 1. Add your download link

Open `index.html`, scroll to the bottom `<script>`, and set:

```js
const APP_LINK = "REPLACE_WITH_YOUR_APP_LINK";
```

Use your Google Play URL, App Store URL, or a direct `.apk` link. Every
"Download" button on the page uses this automatically.

## 2. Host on GitHub Pages (free)

### Option A — dedicated repo (gives you `username.github.io/financeos`)
1. Create a new GitHub repo, e.g. `financeos-landing`.
2. Put `index.html` (this file) in the repo root and push.
3. Repo **Settings → Pages → Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main** / folder: **/ (root)** → **Save**
4. Wait ~1 min. Your site is live at
   `https://<your-username>.github.io/financeos-landing/`.

### Option B — user site (gives you `username.github.io`)
1. Create a repo named exactly `<your-username>.github.io`.
2. Add `index.html` to the root and push. It's live at
   `https://<your-username>.github.io/`.

## 3. (Optional) Custom domain
In **Settings → Pages → Custom domain**, add your domain and create the
matching DNS records your registrar shows.

---

Everything is in `index.html` — no build step, no frameworks, no npm.
