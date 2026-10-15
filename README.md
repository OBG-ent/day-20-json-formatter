# { } JSON Formatter

**Paste ugly JSON. Get pretty, syntax-highlighted JSON. Zero installs.**

Ever copied JSON out of an API response or a log file and gotten a wall of unreadable text on one line? Paste it here, hit **Format**, and get clean, color-coded JSON you can actually read.

## ✨ Features

- **Pretty-print** any JSON with 2-space indentation
- **Syntax highlighting** — keys, strings, numbers, booleans, and nulls each get their own color
- **Minify mode** — squeeze JSON onto one line and see exactly how many bytes you saved
- **Friendly error messages** — tells you *why* your JSON is invalid instead of just failing
- **Stats line** — total key count and character count before/after
- **One-click copy** to clipboard
- **Load sample** button to try it instantly
- Keyboard shortcut: `Ctrl` + `Enter` formats from anywhere

## 🚀 Run it in 30 seconds

No build step, no dependencies, no server.

1. Download or clone this repo
2. Open `index.html` in any browser
3. Paste some JSON and hit **Format**

That's it.

## 🧠 What was practiced

- `JSON.parse()` / `JSON.stringify()` (and the `space` argument for indentation)
- Tokenizing text with regular expressions for syntax highlighting
- Escaping HTML so user input can't break the page (a mini XSS lesson!)
- The Clipboard API (`navigator.clipboard.writeText`)
- Recursive functions (counting nested keys)

## 📁 Files

- `index.html` — the entire app: markup, styles, and logic in one file

---

*Day 20 (simple build) of a daily coding journey — one small project shipped every day.*
