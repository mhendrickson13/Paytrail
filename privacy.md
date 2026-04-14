# PriceTrail Privacy Policy

**Effective date:** April 14, 2026
**Last updated:** April 14, 2026

## Plain English

PriceTrail does not collect, transmit, sell, share, or otherwise process any of your personal information. Everything happens in your browser. Nothing leaves your computer.

## What data PriceTrail handles

When you visit a product page on Amazon, Walmart, eBay, or Best Buy, PriceTrail reads three pieces of information from that page:

1. The product identifier (e.g. an Amazon ASIN)
2. The product title
3. The currently displayed price

This data is stored **exclusively in your browser's local IndexedDB database**. It is not transmitted to PriceTrail's developers, to any third party, to any analytics service, or to any server of any kind.

## What PriceTrail does NOT do

- ❌ Collect your name, email, address, IP, or any identifying information
- ❌ Send your browsing history anywhere
- ❌ Use cookies or tracking pixels
- ❌ Embed analytics SDKs (Google Analytics, Mixpanel, Amplitude, etc.)
- ❌ Read or modify pages outside the four supported retailers
- ❌ Read your saved passwords, autofill data, or browser history
- ❌ Sell or share data with anyone (because there is no data to share)

## Permissions explained

- **`storage`** — required to save price observations to your browser's local IndexedDB and to remember your settings.
- **`activeTab`** — used so the extension popup can read the URL of the tab you're currently viewing.
- **Host permissions** for `*.amazon.com`, `*.walmart.com`, `*.ebay.com`, `*.bestbuy.com` — required so PriceTrail can read product information on those sites only. PriceTrail cannot access any other website.

## Affiliate links

When you click a "Compare elsewhere" or "Open product" link from inside PriceTrail, the link includes the developer's affiliate tag for that retailer. The retailer (Amazon, Walmart, eBay, Best Buy) may pay the developer a small commission if you make a qualifying purchase. The retailers' own privacy policies apply to your interactions on their sites. PriceTrail itself does not see, log, or collect any information about your clicks or purchases.

## Your data is yours

Use the **Clear all** button in the popup to delete every byte of data PriceTrail has stored. Use **Export** to download a copy of your local data. Use **Import** to restore it on another computer.

## Changes to this policy

If this policy ever changes, the new version will be published at this URL with an updated "Last updated" date.

## Contact

Questions about this policy: open an issue at https://github.com/<mhendrickson13>/pricetrail
