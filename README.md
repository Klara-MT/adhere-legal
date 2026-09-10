# ADHERE — legal pages

Static pages for the App Store's required Privacy Policy and Terms of Service URLs.

## Publish (one time, ~5 minutes)

1. In GitHub Desktop: **Add Local Repository** → this folder → **Publish repository**
2. Name it `adhere-legal` and **UNTICK "Keep this code private"** — GitHub Pages
   needs a public repo on a free account, and these pages must be publicly
   readable anyway.
3. On github.com, open the repo → **Settings → Pages** → Source: `Deploy from a
   branch`, Branch: `main`, folder `/ (root)` → Save.
4. Wait a couple of minutes. The site appears at:

```
https://klara-mt.github.io/adhere-legal/
https://klara-mt.github.io/adhere-legal/privacy.html
https://klara-mt.github.io/adhere-legal/terms.html
```

## Where the URLs go

| Where | Which URL |
|---|---|
| App Store Connect → App Privacy → Privacy Policy URL | `/privacy.html` |
| App Store Connect → App Information → License Agreement | `/terms.html` (or Apple's standard EULA) |
| In the app, Settings screen | both |

## Before submitting

- [ ] Read both pages end to end and confirm every statement is true of the shipped app
- [ ] Have the faculty advisor read them
- [ ] Ask whether Penn offers legal review for student organisations
- [ ] If Sentry is NOT in the shipped build, delete section 3 of the privacy policy
- [ ] If the app gains accounts or syncing later, both documents must be revised

## Important

These were drafted for a specific app — local-first, no accounts, no server —
and they are only accurate while that stays true. They are a careful starting
point, not legal advice, and nobody involved in writing them is a lawyer.
