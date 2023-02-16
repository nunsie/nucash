# NuCash 💸

## Overview

NuCash is personal and small business double entry accounting application - inspired by GnuCash.

![krab money](https://media.tenor.com/gDzS_fULerYAAAAC/daireb.gif)

## Features

| Description                                                                                        | Status  |
| -------------------------------------------------------------------------------------------------- | ------- |
| Runs on your local computer, keeping your financial data private and under your control.           | WIP     |
| Refreshingly simple and friendly user interface.                                                   | WIP     |
| Sync transaction data with your bank directly via PSD2 integration.                                | Planned |
| Sync trading data from over 100 bitcoin and crypto exchanges.                                      | Planned |
| Import bank statements in a variety of formats including: CSV, QIF, OFX/QFX, MT940, MT942 & DTAUS. | Planned |
| Easily migrate your existing data from GnuCash.                                                    | Planned |
| Compatible with PTA (plain text accounting) software files like ledger-cli, hledger & beancount.   | Planned |
| Quote feeds for stocks, bonds, ETFs, currencies, crypto, etc.                                      | Planned |

## Downloads

- Mac: (coming soon)
- Windows: (coming soon)
- Linux: (coming soon)

## Motivation

I started this project out of a new found interest in my personal finances.

I could not find any free, simple, easy to use, offline storage with online transaction syncing accounting software. Most of the options out there cost way too much, try to do more than I really care for and aren't really user friendly.

GnuCash came really close, but I quickly ran into a few issues:

- Unable to easily import financial statements from my bank, brokers and crypto exchanges.
- No support for crypto currencies.
- Unable to sync price feeds for stock and currency quotes.
- Lots of crashes.
- Reporting is pretty basic and bland.
- UI is pretty dated.

I don't hate it, I just think it could be better.

Additionally, I've been meaning to learn Rust for a long time now and I thought this would be the perfect way to scratch that itch and take the plunge.

## Development

To run this project locally in development mode:

1. Clone this repository

```bash
git clone https://github.com/nunsie/nucash.git
```

2. Install NPM dependencies

```bash
npm i
```

3. Run the local development server

```bash
npm run tauri dev
```
