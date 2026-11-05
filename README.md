# Discord

Sign in to PeltyCMS with Discord

Official single sign-on for [PeltyCMS](https://github.com/MythicalLTD/PeltyCMS).

## Why this addon

Teams that want one-click login with an identity provider customers already use.

## Features

- Client and staff sign-in with **Discord**
- OAuth / OIDC redirect + session handled by Pelty
- Account linking for existing customers
- Sandboxed WASM SSO provider

## How it works

1. Install **Discord** from the [Mythical marketplace](https://market.mythicalsystems.org/marketplace/product/sso-discord) inside Pelty Admin → Addons.
2. Open Pelty Admin → Authentication, create a Discord app, paste client id/secret, and enable the SSO button.
3. Customers hit checkout / login / order flow as usual — Discord runs in the background.

## Requirements

- PeltyCMS with WASM addons enabled
- Working Discord credentials
- Outbound HTTPS from your panel

## Get it

**[Discord on Mythical Marketplace](https://market.mythicalsystems.org/marketplace/product/sso-discord)**

## Support

Bugs and questions for this addon → Issues on this repo.  
PeltyCMS core → https://github.com/MythicalLTD/PeltyCMS
