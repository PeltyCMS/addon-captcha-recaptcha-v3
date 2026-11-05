# Google reCAPTCHA v3

Official **PeltyCMS** `captcha` WASM addon (`captcha-recaptcha-v3`).

## Install

1. Open Pelty Admin → Addons → Marketplace
2. Set registry URL to `https://market.mythicalsystems.org/api/pelty/addons/registry.json`
3. Download **Google reCAPTCHA v3**

Marketplace: https://market.mythicalsystems.org/marketplace/product/captcha-recaptcha-v3  
Product ID (CI): `45`

## Develop

This repository is a git submodule of [MythicalLTD/PeltyCMS](https://github.com/MythicalLTD/PeltyCMS) at `extensions/addons/captcha-recaptcha-v3`.

```bash
# from the PeltyCMS monorepo
cargo xtask addons captcha-recaptcha-v3
```

## Release (Mythic Marketplace)

Same flow as [featherpanel-com/PterodactylPanelApi](https://github.com/featherpanel-com/PterodactylPanelApi):

1. Repo secrets: `MYTHIC_PRODUCT_ID`, `MYTHIC_RELEASE_TOKEN`
2. Repo variable: `ADDON_DIR=captcha-recaptcha-v3`
3. Actions → **Release Addon** → Run workflow

Publishes the packed `captcha-recaptcha-v3.zip` via `MythicalLTD/.github/actions/publish-release@v1` and creates a GitHub Release.
