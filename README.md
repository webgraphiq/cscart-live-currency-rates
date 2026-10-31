# Live Currency Rates with Modifier for CS-Cart

**🛑 PREMIUM ADD-ON: This repository does not contain the open-source code. It serves as the official listing and documentation page for the WebGraphiq premium add-on.**

**Live Currency Rates with Modifier** is an automated FX rates and currency-margin add-on for CS-Cart and Multi-Vendor. It refreshes secondary currencies from a live provider, then applies an optional absolute or percent modifier so storefront prices are not the raw mid-market rate.

## [🛒 Buy & View Live Demo](https://www.webgraphiq.com/live-currency-rates-with-modifier-v4.html)

One-time license. The current price and the live demo are on the product page.

## Why store owners use it

- Keep secondary currencies up to date without editing rates by hand.
- Add a margin on top of the fetched rate (absolute value or percent).
- Choose a rate provider: European Central Bank, X-Rates, or Open Exchange Rates (er-api.com).
- Per-currency **Autoupdate** — only the currencies you mark are refreshed.
- Update on a schedule via cron, or let the storefront refresh (minimum interval applies unless you run a test update).
- Saving a currency in Administration → Currencies can trigger an immediate update when licensed.
- No CS-Cart core file edits.

## Providers

- **European Central Bank** — daily XML rates (EUR base).
- **X-Rates** — calculator-based rate fetch.
- **Open Exchange Rates (er-api.com)** — JSON API (replaces the old exchange-rates.org HTML scrape, which servers can no longer load reliably).

## Modifier and admin fields

On each secondary currency you can see and set:

- **Autoupdate** — include this currency in automatic refreshes.
- **Modifier** and **modifier type** (absolute or percent) when the global modifier option is on.
- **Original rate** — the fetched coefficient before your margin.
- **Last update** timestamp.

## Cron and storefront update

- Enable **Update rates thru Cron job**, set a password, and use the PHP CLI / wget / curl examples on the settings screen (admin URL).
- Suggested schedule: about every hour, or whatever fits your shop.
- When cron is enabled, storefront auto-update is skipped so the job owns the refresh.

## Requirements

- CS-Cart or Multi-Vendor **4.12.1** or newer, including **4.21**
- PHP **8.3** or a current 8.x release used by that shop
- At least one secondary currency with Autoupdate enabled for automatic refresh

## This repository

<p align="center">
  <a href="https://www.webgraphiq.com/live-currency-rates-with-modifier-v4.html">
    <img alt="Buy and view the live demo" src="https://img.shields.io/badge/CS--Cart-Buy%20%26%20View%20Live%20Demo-28a745?style=for-the-badge&labelColor=1A365D">
  </a>
</p>

<p align="center"><strong>One-time license · live FX rates with your margin</strong></p>

This is the public product listing. The add-on package, license checks, and source files are not published here. After purchase, the package is readable PHP under the WebGraphiq commercial license, installed from your WebGraphiq account.

Support: [webgraphiq.com](https://www.webgraphiq.com) · webgraphiq@gmail.com

© WebGraphiq. All rights reserved. [License](https://www.webgraphiq.com/license.html)

## Other Premium CS-Cart Add-ons by WebGraphiq

More CS-Cart and Multi-Vendor add-ons are listed on the [WebGraphiq GitHub profile](https://github.com/webgraphiq).
