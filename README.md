# Google reCAPTCHA v3

Stop bots on PeltyCMS forms with Google reCAPTCHA v3

Official **captcha / bot protection** for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) — identifier `captcha-recaptcha-v3`.

## Why this addon

Anyone tired of spam accounts and bot ticket floods.

## Features

- Protect login, register, tickets and checkout with **Google reCAPTCHA v3**
- Server-side verification inside the WASM captcha addon
- Site keys configured once in Pelty settings
- No theme PHP hacks

## How it works

1. Install **Google reCAPTCHA v3** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v3) (or Pelty Admin → Addons → Marketplace).
2. Open Pelty Admin and enter your Google reCAPTCHA v3 credentials in the addon settings.
3. Attach it to the products / forms / login flows you care about.
4. New orders and sign-ins use Google reCAPTCHA v3 automatically.

## Requirements

- A running PeltyCMS panel with WASM addons enabled
- Valid Google reCAPTCHA v3 API / OAuth / panel credentials (depending on the integration)
- Outbound HTTPS from the panel to Google reCAPTCHA v3

## Get it

[Google reCAPTCHA v3 on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v3)

Free official build. Source for this package lives in this repository.

## Support

- Marketplace product page: https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v3
- PeltyCMS core: https://github.com/MythicalLTD/PeltyCMS
- Issues for this addon: use this repo’s Issues tab
