# NOVA Finder

A **custom search engine** with extra commands, timers, and a clean UI.  
👉 Use it directly as your search engine: [https://nova-finder.baptiste-reb.fr/](https://nova-finder.baptiste-reb.fr/)

---

## 🚀 Features
- Minimalist search bar with custom background.
- Special commands for productivity:
  - `!ia [query]` → Search with AI (Perplexity).
  - `!timer [minutes]` → Start a countdown timer with desktop notification.
  - `!trans [text]` → Translate text using Google Translate (auto-detect → French).
- Input focus always returns to the search bar for fast usage.
- TailwindCSS-based modern UI.

---

## 🔧 Setup in your browser

You can set **NOVA Finder** as your default search engine in Brave, Chrome, or any Chromium-based browser:

1. Open **Settings → Search engine → Manage search engines and site search**.
2. Click **Add** and fill in:
   - **Name**: `NOVA Finder`
   - **Shortcut**: `nova` (or any keyword you like)
   - **URL with %s in place of query**:  
     ```
     https://nova-finder.baptiste-reb.fr/?search=%s
     ```
3. Click the **⋮ menu** next to your new engine and select **Set as default** (optional).

---

## 🎯 Usage examples
- Typing `hello world` → standard Google search.
- Typing `!ai quantum computing` → opens Perplexity with the query.
- Typing `!timer 5` → starts a 5-minute countdown.
- Typing `!trad hello` → opens Google Translate with "hello" translated to French.

---

## 📌 Notes
- Desktop notifications (used by timers) require allowing notifications for the site.
- Works best on `https://nova-finder.baptiste-reb.fr/` (secure context). Notifications may not work in `file://` mode.
