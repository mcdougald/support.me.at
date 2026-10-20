<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="support.me.at landing page" width="880">
  </picture>
</p>

<h1 align="center">support.me.at</h1>

<p align="center"><strong>It is all free to use. Sponsors are how it stays maintained.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-live-171717?style=flat-square" alt="Status: live">
  <img src="https://img.shields.io/badge/license-source--available-404040?style=flat-square" alt="License: source-available">
  <img src="https://img.shields.io/badge/part%20of-me.at-737373?style=flat-square" alt="Part of me.at">
</p>

<p align="center">
  <a href="https://support.me.at">Website</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#built-with">Built with</a>
</p>

Donate pages tend to push: goal bars, running totals, a card form on the page. I built support.me.at as a small, static sponsor hub for my work: open-source libraries, the me.at apps, and the notes around them. It says what the work is and where support goes, then points to the funding platforms people already use. Nothing is collected on the page itself, every link opens the platform's own site, and there is deliberately no goal, running total or thermometer.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/overview-dark.svg">
    <img src=".github/assets/overview.svg" alt="support.me.at at a glance: six ways to give, never takes a payment, no goal or thermometer, free ways to help" width="880">
  </picture>
</p>

## Why support.me.at

| The usual donate page | support.me.at |
| --- | --- |
| A goal bar and a running total | No goal, total or thermometer |
| A card form on the page | Links out only; nothing is collected here |
| One platform | Six platforms, labelled one-time or monthly |
| Money is the only way to help | Free ways to help, listed alongside |

## Features

- **Six funding platforms**: GitHub Sponsors, Open Collective, Buy me a coffee, Ko-fi, Patreon and Liberapay, each labelled with whether it is one-time or monthly.
- **Where it goes**: three short lines on what support pays for, from open-source maintenance to keeping the me.at apps running and free.
- **Free ways to help**: starring and following the work on GitHub, for people who would rather not give money.
- **Sponsor acknowledgement wall**: an optional static thank-you wall, generated offline from a local payload with no tokens at runtime.
- **Never takes a payment**: the page only links out; no checkout, no card fields, no tracking of amounts.
- **Accessible by design**: every outbound card carries an explicit accessible name that discloses it opens in a new tab.

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow.svg" alt="How support.me.at works: read, choose, give, thanks" width="880">
  </picture>
</p>

The page is one fully static route, with its copy and link data validated by Zod. It says what the work is and where support goes, then lists six platforms labelled one-time or monthly, and every card opens the platform's own site in a new tab. The optional thank-you wall is generated offline from a local payload, so it needs no tokens at runtime.

## Built with

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-19-171717?style=flat-square&logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TypeScript-5-262626?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-404040?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4">
  <img src="https://img.shields.io/badge/Zod-validated-525252?style=flat-square&logo=zod&logoColor=white" alt="Zod">
</p>

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- Zod for validating the page's copy and link data
- Fully static, one route

## Part of the me.at family

support.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

Source-available. See [LICENSE](LICENSE).
