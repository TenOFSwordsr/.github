<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=DotGothic16&weight=400&size=22&duration=3500&pause=900&color=00F59B&center=true&vCenter=true&width=820&height=62&lines=ten%20swords%20in%20the%20back%20%E3%83%BB%20still%20shipping;lean%20runtimes%20%E3%83%BB%20stealth%20sockets%20%E3%83%BB%20silent%20daemons;46%20repositories%20%E3%83%BB%20documentation%20first%20%E3%83%BB%20zero%20fluff;the%20worst%20is%20over%20%E3%83%BB%20see%20you%20on%20the%20next%20hop%20%E2%99%A1)](https://github.com/orgs/TenOFSwordsr/repositories)

# ten of swords ・ TenOFSwordsr

**lean runtimes ・ stealth sockets ・ silent daemons ・ best parsed over an encrypted wire ♡**

[![repositories](https://img.shields.io/badge/repositories-46-00f59b?style=for-the-badge&logo=github&logoColor=042f22)](https://github.com/orgs/TenOFSwordsr/repositories)
[![project index](https://img.shields.io/badge/project%20index-readable-00f59b?style=for-the-badge&logo=readme-dot-cc&logoColor=042f22)](https://github.com/orgs/TenOFSwordsr/repositories?tab=readme)
[![languages](https://img.shields.io/badge/Mojo%20%2B%20Go%20%2B%20Python%20%2B%20Kotlin-00f59b?style=for-the-badge&logo=python&logoColor=042f22)](https://github.com/orgs/TenOFSwordsr/repositories?language_sort=)
[![no trackers](https://img.shields.io/badge/no%20trackers%20%2B%20no%20analytics-00f59b?style=for-the-badge&logo=ghost&logoColor=042f22)](#TenOFSwordsr)

<img src="assets/ten-of-swords-rws.jpg" width="240" alt="The Ten of Swords, Rider-Waite-Smith" />

</div>

---

everything published here is documentation-first. each repository carries a README that says what the thing is, what stack it uses, and what state it is in - active, finished, experimental, or build output. nothing is presented as more finished than it is, and the dead experiments stay up because they are the interesting part.

the taste is the same across all of it: when a scraper demands 300 megabytes of Chromium, write a browser in Mojo that runs in 21. when traffic has to cross aggressive filtering, build tunnels that refuse to drop. when a routine repeats twice, hand it to a loop and walk away. small binaries, clean sockets, quiet machines.

---

### 🗡️ stealth, scraping & data

* **[hjs-stealth-browser](https://github.com/TenOFSwordsr/hjs-stealth-browser)** : a stealth headless browser with real JS execution - client-hint, header and TLS-cipher-rotation profiles that match the browser they claim to be.
* **[hbrowser](https://github.com/TenOFSwordsr/hbrowser)** : the same idea at one tenth the size: fetch, strip, parse, emit JSON. no JS, no rendering, ~21 MB RSS.
* **[clinic-import-api](https://github.com/TenOFSwordsr/clinic-import-api)** : WordPress plugin exposing a key-authenticated REST namespace for upserting a medical directory, with an idempotent import ledger.
* **[cookma-scraper-bugfix](https://github.com/TenOFSwordsr/cookma-scraper-bugfix)** : price-feed scrapers with a 19-check regression suite and a pytest-free runner - the most tested code in the org.
* **[csv-price-sync-php-port](https://github.com/TenOFSwordsr/csv-price-sync-php-port)** : dependency-free PHP port of those scrapers for a host that could not run Python.
* **[woocommerce-csv-price-sync](https://github.com/TenOFSwordsr/woocommerce-csv-price-sync)** : OpenCart/WooCommerce bulk price and stock synchronisation from dated CSV feeds.
* **[centris-realtime-listings](https://github.com/TenOFSwordsr/centris-realtime-listings)** : Montreal real-estate listing scraper with a session-warming bypass, Google Sheets as the datastore, and an offline demo mode with tests.
* **[linkedin-search](https://github.com/TenOFSwordsr/linkedin-search)** : Go + Gin + SQLite/FTS5 search over an exported profile dataset. The export is not scraped here.

### 📈 markets & signals

* **[tsetmc-market-report-generator](https://github.com/TenOFSwordsr/tsetmc-market-report-generator)** : TSETMC equity/option screener producing RTL Excel reports on buyer power over 30-second trade windows.
* **[etemad-bourse](https://github.com/TenOFSwordsr/etemad-bourse)** : the packaged release of the same engine: Python desktop app, Go worker, dashboard, Android client, deploy and Playwright test tooling.
* **[ema-alert-server](https://github.com/TenOFSwordsr/ema-alert-server)** : Go relay that turns broker webhooks into Telegram and SMS alerts, with a read-only walk monitor.
* **[ema-alert-remote](https://github.com/TenOFSwordsr/ema-alert-remote)** : the MQL5 Expert Advisor and its include library that emits those alerts from the terminal.
* **[ema-alert-ea](https://github.com/TenOFSwordsr/ema-alert-ea)** : the current EA build, including chart-follow and telemetry modules.
* **[mt5-alert-watchdog](https://github.com/TenOFSwordsr/mt5-alert-watchdog)** : keep-alive and backfill: notices when the terminal goes quiet and replays what was missed.
* **[boursefilter-android](https://github.com/TenOFSwordsr/boursefilter-android)** : Kotlin WebView shell for the TSETMC dashboard.
* **[remote-auto-trader](https://github.com/TenOFSwordsr/remote-auto-trader)** : signal-driven execution loop with an LLM pre-trade veto layer and an explicit anti-chasing rule.

### ⚕️ pharmacology & documents

* **[pharma](https://github.com/TenOFSwordsr/pharma)** : the collection: monograph OCR, handwritten-note transcription, handbook generation, directory scrapers, substance reference.
* **[pharm-handbook-pipeline](https://github.com/TenOFSwordsr/pharm-handbook-pipeline)** : page population, cleanup and assembly for a 182-drug handbook in three editorial variants.
* **[mini-monograph-ocr](https://github.com/TenOFSwordsr/mini-monograph-ocr)** : extraction of a 617-page Persian drug monograph into Markdown, with RTL column reflow under printed captions.
* **[persian-pharm-transcripts](https://github.com/TenOFSwordsr/persian-pharm-transcripts)** : 182 pages of handwritten pharmacology notes, transcribed, plus the Node DOCX generator.

### 🖧 systems, tunnels & boxes

* **[wsl-rdp-panel](https://github.com/TenOFSwordsr/wsl-rdp-panel)** : boots a WSL2 desktop, port-proxies it to loopback, and launches the session.
* **[mojomc-server](https://github.com/TenOFSwordsr/mojomc-server)** : a native Minecraft server with no JVM and no Python runtime on the box.
* **[skymine-server-panel](https://github.com/TenOFSwordsr/skymine-server-panel)** : Go panel talking to the Docker socket, serving an embedded Svelte SPA, plus a Velocity plugin.
* **[skymine-minecraft-plugin](https://github.com/TenOFSwordsr/skymine-minecraft-plugin)** : auto-resetting mines for Paper, with the deploy scripts that put it on the host.
* **[rx6800-miner-launchers](https://github.com/TenOFSwordsr/rx6800-miner-launchers)** : launch profiles that keep an RX 6800 clocks-and-power sane enough to still use the desktop.
* **[telegram-export-to-sqlite](https://github.com/TenOFSwordsr/telegram-export-to-sqlite)** : HTML export to SQLite with FTS5, for archives that have to be searched rather than scrolled.

### ☕ bots & small machines

* **[dnd-companion-bot](https://github.com/TenOFSwordsr/dnd-companion-bot)** : runs a D&D table inside Telegram.
* **[dnd-telegram-bot](https://github.com/TenOFSwordsr/dnd-telegram-bot)** : character creation and stat keeping for the same table.
* **[telegram-perplexity-bot](https://github.com/TenOFSwordsr/telegram-perplexity-bot)** : research queries through two models, one of them a deep-research loop.
* **[telegram-hello](https://github.com/TenOFSwordsr/telegram-hello)** : the 40-line starting point all of the above grew out of.
* **[job-auto-apply-extension](https://github.com/TenOFSwordsr/job-auto-apply-extension)** : Manifest V3 extension targeting three Iranian job boards. Background and popup only - the content scripts were never written.

---

### 🌿 runtime & toolbox

* **languages & runtimes** : Mojo, Go, Python, Kotlin, QuickJS, C-FFI, PHP, Bash, PowerShell
* **stealth & scraping** : client-hint and header rotation, TLS cipher-suite matching, cookie jars, JA3/JA4 fingerprinting, Playwright, Selenium, plain `urllib` when it is enough
* **systems & networks** : Debian, Windows Server, WireGuard and AmneziaWG, DPI-evasion tuning, VMware, WSL2, Pterodactyl
* **data & documents** : PostgreSQL, MySQL, SQLite/FTS5, openpyxl RTL workbooks, PyMuPDF, Tesseract, python-docx
* **markets** : TSETMC, MetaTrader 5, Binance, DexScreener, GMGN, TabDeal, altFINS
* **telemetry & automation** : Telegram bot daemons, systemd units, n8n pipelines, unattended loops

---

<div align="center">

*the worst is over ・ ten swords, still shipping ・ see you on the next hop ♡*

*no names, no email, no analytics on this page - judge the code instead*

</div>
