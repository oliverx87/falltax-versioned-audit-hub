# Falltax v1.0.0 - sovereign legal workflow tool 2026

> **Falltax is a browser-based return management app for sovereign legal work, pairing offline local storage, conflict checks, and a versioned audit trail in v1.0.0.**

[![Platform](https://img.shields.io/badge/Platform-browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v1.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliverx87/falltax-versioned-audit-hub?style=flat-square)](https://github.com/oliverx87/falltax-versioned-audit-hub)

---

<p align="center">
  <a href="https://oliverx87.github.io/falltax-versioned-audit-hub/">
    <img src="https://img.shields.io/badge/Download-Falltax%20Latest-brightgreen?style=for-the-badge" alt="Download Falltax">
  </a>
</p>

> **[Direct Download - Falltax v1.0.0](https://oliverx87.github.io/falltax-versioned-audit-hub/)**

---

[Download Latest Build](https://oliverx87.github.io/falltax-versioned-audit-hub/)

---

## Overview

Falltax is packaged as a single-file browser application for managing returns within a sovereign legal workflow. Everything stays in the browser, which means there is no server to maintain, no account creation step, and no telemetry system to set up.

It is intended for attorney firms and legal teams that want organized return tracking, support for US law research, and a dependable local history of activity. The app centers on local-first storage, straightforward workflow controls, and an audit chain that can be exported whenever it is needed.

---

## What it offers

- Operates entirely in the browser with no server-side component
- Continues working offline after load, with data kept locally
- Handles multiple returns with search and filtering capabilities
- Highlights critical dates to keep work on schedule
- Provides conflict scanning and advice issuance support
- Writes hashed audit entries for a traceable activity record
- Uses IndexedDB for storage, with a localStorage fallback when required
- Includes practice areas, strategic weaves, and a US law corpus
- Syncs across sibling tools through broadcast-channel messaging
- Exports JSON audit chains and can seed demo data for testing

---

## Installation

Falltax is distributed as a browser app and is meant to be used as a single-file tool.

1. Download or clone the repository.
2. Open the main HTML file in a modern browser.
3. Grant local storage access if your browser asks for it.

If you are using the hosted build, you can launch the app straight from the download page without any extra setup.

---

## How to use it

A common workflow looks like this:

1. Open the app in your browser.
2. Create a new return or load one that already exists.
3. Use search and filters as the number of returns increases.
4. Check conflict results before issuing advice.
5. Watch key dates and follow the audit trail.
6. Export the JSON audit chain when you need a portable record.

For demos or testing, the included seed data can be used to fill the workspace quickly.

---

## Storage and configuration

Falltax keeps its data in browser storage instead of relying on a separate configuration service.

- Primary storage: IndexedDB
- Fallback storage: localStorage
- Shared updates: broadcast-channel sync across sibling tools

To reset the application state, clear the site's browser storage for the repository origin. Demo seeding is available whenever you want a fresh sample dataset.

---

## System requirements

- A modern browser with support for HTML app features
- IndexedDB support recommended for full local storage behavior
- localStorage available as a fallback
- Internet access only for the initial download or page load
- Enough local storage space for returns, audit history, and corpus data

---

## FAQ

### Do I need an account to use Falltax?
No. It is built to work without signup or identity-based onboarding.

### Does it collect usage data?
According to the product profile, it has no telemetry.

### Can it run offline?
Yes. After the app has loaded in the browser, it is intended to operate offline.

### Where does Falltax keep data?
Data stays locally in the browser using IndexedDB, with localStorage as the fallback.

### How can I transfer or inspect audit history?
Export the audit chain as JSON, then store or review it outside the app as needed.

### What should I do if storage or sync behavior looks off?
Verify browser permissions, make sure storage is available, and reload the app in a supported browser. If necessary, clear local site data and re-seed the demo content.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
