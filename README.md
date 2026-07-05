# Skintel AI — Privacy Policy Page

A single-file, dependency-free HTML privacy policy for the Skintel AI iOS app.
Used to satisfy the App Store Connect **Privacy Policy URL** requirement.

## Files
- `index.html` — the privacy policy page (self-contained, inline CSS)

## Before you publish — fill in these placeholders
Search `index.html` for the brackets and replace:

- `[Effective Date]` — e.g. July 5, 2026
- `[Developer / Company Name]` — your name or company (e.g. Saksham / your registered entity)
- `[Contact Email]` — a real support/contact email you can receive mail at
- Section 3 (How Your Photos Are Handled) — describe your **actual** practice:
  whether images are processed on-device or on a server, whether they are
  stored or deleted, and for how long. This must be accurate.
- Section 4 (Third-Party Services) — list your real providers
  (e.g. Apple, Firebase, your AI/analysis processor)
- `[Optional: mailing address]` — remove if not needed

## How to host (pick one, all free)

### GitHub Pages
1. Create a public repo, add `index.html`.
2. Repo → Settings → Pages → Source: `main` branch, root.
3. Your URL will be `https://<username>.github.io/<repo>/`.

### Netlify / Vercel / Cloudflare Pages
1. Drag-and-drop the folder (or connect the repo).
2. Copy the deployed URL.

## Use in App Store Connect
Paste the final public URL into:
- App Store Connect → your app → **App Privacy** / App Information → **Privacy Policy URL**
- The same URL should also be reachable from inside the app (e.g. on the paywall/settings screen).

## Important
This is a general template, not legal advice. The photo/biometric handling
disclosures matter for Apple review and for privacy law — make sure Section 3
reflects exactly what your app does. Consider a legal review if you can.