<div align="center">

# creoCMS

### Websites without the database drama.

A fast, flat-file CMS for business sites, portfolios and shops.<br>
**Buy once, updates forever.**

[![Buy creoCMS](https://img.shields.io/badge/Buy_creoCMS-cms.creoprime.com-22c55e?style=for-the-badge)](https://cms.creoprime.com/)
[![Try the demo](https://img.shields.io/badge/Try_the_demo-demo.creoprime.com-111111?style=for-the-badge)](https://demo.creoprime.com/)
[![Made by](https://img.shields.io/badge/Made_by-creoprime.com-0b6b83?style=for-the-badge)](https://creoprime.com/)

![In development since 2010](https://img.shields.io/badge/in_development_since-2010-555)
![PHP 8.0+](https://img.shields.io/badge/PHP-8.0%2B-777bb4?logo=php&logoColor=white)
![No database](https://img.shields.io/badge/database-none-22c55e)
![12 themes](https://img.shields.io/badge/themes-12-blue)
![Languages](https://img.shields.io/badge/languages-EN_%7C_PL-orange)
![Licence](https://img.shields.io/badge/licence-commercial-lightgrey)

</div>

---

**creoCMS** is a system I have been making since 2010. I make all my projects for clients in it, unless I am explicitly told to use another system. [creoprime.com](https://creoprime.com/) runs on it too.

It is built to be fast, safe, and easy to look after—for me and for the people who use it every day.

> [!NOTE]
> **This repository is the public home of creoCMS, not its source code.** The code is closed and sold under a licence at [cms.creoprime.com](https://cms.creoprime.com/). Here you'll find what it does, how it's built and where to get it.

<img width="1287" height="1116" alt="creoCMS screenshot" src="https://github.com/user-attachments/assets/0fbda94d-8b46-432a-b2ed-af3c498ef08c" />

## 🛒 Get creoCMS

| | |
|---|---|
| **Buy** | [cms.creoprime.com](https://cms.creoprime.com/) – one payment, no subscription, an early-adopter price for the first buyers |
| **Try first** | [demo.creoprime.com](https://demo.creoprime.com/) – the full admin panel, a private copy for every visitor |
| **What you get** | 1 domain + 1 staging domain · every feature and theme · updates forever |
| **Pay in** | PLN, EUR, GBP or USD – card, BLIK and more, through Stripe |
| **Need it built for you?** | I make websites on creoCMS – [creoprime.com](https://creoprime.com/) |

---

## Key Features

### ⚡ Light and Fast
* **No database:** Everything is kept in plain files, so a site is quick, cheap to host, easy to back up, and easy to move.
* **Pictures done for you:** Uploaded photos are turned into modern AVIF and WebP formats in several sizes, so pages load fast on phones too.
* **No heavy frameworks:** Small, hand-written code that runs on PHP 8.0 up to the newest version.

### 👥 Easy for Clients
* **A simple admin panel:** Clients change their own texts, pictures, posts, and news without touching code and without breaking the layout.
* **Only what they need:** I choose which texts each client can edit and under which names, and every account gets only the parts it is allowed to use.
* **Rich visual editor:** Features headings, lists, links, images, videos, and a spell check in the right language.
* **Nothing gets lost:** Version history, a trash bin for deleted items, and an activity log of who changed what.

### 🔒 Accessible and Private
* **Accessible (WCAG):** Readable colors, full keyboard use, and screen reader friendly on every theme.
* **Private by default:** No tracking without consent, and videos/maps from other services load only after a visitor allows it.
* **GDPR ready:** A cookie notice with real choices, a privacy policy that follows the features you switch on, and sign-up lists with double opt-in.
* **Safe:** Protected forms, cleaned uploads, spam protection without tracking, and regular security reviews.

### 🌐 Many Languages, Many Looks
* **Multilingual:** Every page, post, and project available in each language, with the visitor's language chosen automatically.
* **Themes:** A growing set of designs—from clean business sites to game studios, a vet clinic, or a portfolio. A single page can even have its own look.
* **Content stays when the look changes:** FAQ, prices, team and other sections belong to the site, so switching the theme only changes the design. Themes offer their own settings, such as light / dark mode and accent colours.

### 🚀 Everything a Modern Site Needs
* **Blog or Devlog:** Includes series, tags, scheduled posts, comments, reactions, and RSS feeds.
* **Projects and Portfolio:** Showcases games, tools, and websites with store buttons, roadmaps, changelogs, downloads, and a printable CV page.
* **Reaching People:** A release list that sends announcements in the background, Discord announcements, and social links.
* **Shop:** Digital products with Stripe Checkout, invoice details, discount codes, limited offers and the EU 30-day lowest-price rule shown automatically.
* **Additional Modules:** Bookings, galleries, maps, polls, a news banner, and files for download—each switched on only where needed.

<img width="1277" height="1105" alt="creoCMS screenshot" src="https://github.com/user-attachments/assets/1339106d-8e37-44c9-938d-8127e47a866f" />

---

## 🛠️ Under the Hood

| Area | How it's done |
|---|---|
| **Storage** | Plain PHP and JSON files, written atomically – no database server. SQLite only for shop orders. |
| **Licences** | Licence files signed with Ed25519 (libsodium) and checked offline on the buyer's server. |
| **Updates** | One click in the panel. Each release is signed and verified, the site is backed up first, then health-checked – and rolled back automatically if it doesn't answer correctly. A separate recovery script covers the worst case. |
| **Features** | Self-contained modules (shop, blog, booking, gallery…) that hook into slots in any theme. |
| **Themes** | 12 themes ship today: creoForge, creoGrunge, creoLaunch, creoMinimal, creoNova, creoPlay, creoPortfolio, creoSarab, creoVault, creoVet, creoWind, creoWriter. |
| **Payments** | Stripe Checkout with signed webhooks; licences and downloads delivered automatically after payment. |
| **Demo** | Every visitor of the demo gets a private, throwaway copy of a full site. |

<img width="2133" height="1203" alt="image" src="https://github.com/user-attachments/assets/e2a791e3-3865-400e-8562-b7a0e950ef21" />


---

<div align="center">

**creoCMS** is designed, built and maintained by me since 2010.

[Buy creoCMS](https://cms.creoprime.com/) · [Try the demo](https://demo.creoprime.com/) · [About me](https://creoprime.com/)

<sub>© creoCMS. All rights reserved. The source code is not public.</sub>

</div>
