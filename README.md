# ShiftWeb

Static site for the Shift iOS app: landing page, privacy policy and support, in English and Spanish. Plain HTML and one stylesheet — no build step, no JavaScript, no external requests.

## Deploy (Cloudflare Pages)

1. Create a Pages project from this repository.
2. Framework preset: **None**. Build command: *(empty)*. Output directory: `/`.
3. Custom domains → `shift.diegodesalas.com`.

Pages serves `privacy.html` at `/privacy`, so the App Store Connect URLs are:

| | English | Spanish |
|---|---|---|
| Privacy | `https://shift.diegodesalas.com/privacy` | `https://shift.diegodesalas.com/es/privacy` |
| Support | `https://shift.diegodesalas.com/support` | `https://shift.diegodesalas.com/es/support` |

## Keep in sync with the app

The privacy policy states that Shift collects nothing and uses only the user's private iCloud database. If the app ever adds analytics, accounts, a server, or subscriptions, update both privacy pages — and the App Privacy answers in App Store Connect — **before** that version ships.
