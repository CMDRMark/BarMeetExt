# BarMeetExt

Public site for the **BarMeet** Chrome extension (Google OAuth app name: **BarMeetExt**).

Hosted on GitHub Pages at:

| Page | URL |
|------|-----|
| **Application home** (use in OAuth consent screen) | https://cmdrmark.github.io/BarMeetExt/ |
| **Privacy policy** | https://cmdrmark.github.io/BarMeetExt/privacy.html |

Do **not** use `https://cmdrmark.github.io/` alone as the home page unless you create a separate `cmdrmark.github.io` GitHub Pages user site repo. That root URL 404s today.

## Google OAuth verification checklist

1. Push `main` and confirm Pages serves the URLs above.
2. **Search Console** → add property **URL prefix** `https://cmdrmark.github.io/BarMeetExt/` → verify with the HTML meta tag in `index.html` (already included).
3. Wait **24 hours** after verification before resubmitting OAuth verification.
4. **Google Cloud** → OAuth consent screen:
   - Application home page: `https://cmdrmark.github.io/BarMeetExt/`
   - Privacy policy: `https://cmdrmark.github.io/BarMeetExt/privacy.html`
   - Authorized domains: `cmdrmark.github.io` (no `https://`)
   - App name **BarMeetExt** must match the homepage title, or rename the OAuth app to **BarMeet** and update the homepage wording to match.
5. Resubmit app verification with a short demo video (Connect → meetings → Start meeting → Sign out).

## Enable GitHub Pages

1. Push this repo to `main`
2. GitHub → **Settings** → **Pages**
3. Source: **Deploy from a branch** → `main` / `/ (root)`

## Files

- `index.html` — public application home (no login)
- `privacy.html` — privacy policy for Google / Chrome Web Store
- `PRIVACY_POLICY.md` — Markdown copy of the policy
