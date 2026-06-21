# Bulk Link Opener

A tiny, single-file HTML tool to manage and open a list of links — no account, no backend, no dependencies. Just open the file in your browser and go.

I built this to solve my own problem: I had a long list of links saved in a notepad and didn't want to open each one manually or sign up for any service to track them. Everything runs locally in your browser and saves your progress automatically.

## Features

- **Paste any list of links** — one per line
- **Optional titles** — format a line as `Title | https://link` to show clean names instead of raw URLs
- **Clickable list** — open any link directly with a click
- **Next Unwatched** — step through links in order, one at a time
- **Random Unwatched** — pick a random link you haven't opened yet
- **Progress tracking** — opened links get marked and greyed out automatically
- **Search** — filter your list by title instantly
- **Auto-save** — your links and progress persist in the browser, so it's all still there next time you open it

## How to use

1. Download `index.html`
2. Open it in any browser (double-click, or use a live server)
3. Paste your links, click **Load / Update List**, and start clicking

That's it. No install, no signup, no internet required after the page loads.

## Tech

Plain HTML, CSS, and JavaScript in a single file. Progress is stored using the browser's `localStorage`, so it stays on your own machine.

## Note

Saved data lives in the browser you use it in. Switching browsers or clearing browsing data will reset your saved list and progress.

## License

MIT — free to use, modify, and share.
