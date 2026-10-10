# Focus Log

A simple study-session tracker. Start a timer, log what you studied, and see where your week went.

**Live demo:** https://sunshiamathur.github.io/focus-log/

<!-- Add a screenshot: take one of the live site, upload it to the repo as screenshot.png, then uncomment the next line -->
<!-- ![Focus Log screenshot](screenshot.png) -->

## Features

- **Session timer:** start and stop a timer for any subject and save the session automatically
- **Custom subjects:** add your own subjects (e.g. Calculus, Reading, Coding)
- **7-day chart:** a bar chart of minutes studied per day over the last week
- **Session history:** view and delete recent sessions
- **Saved in your browser:** data persists between visits using `localStorage`, with no account needed
- **Light and dark mode:** follows your system theme
- **Responsive and accessible:** works on phones and desktops, with keyboard focus styles and labeled controls

## Built with

- HTML, CSS, and vanilla JavaScript (no frameworks or build step)
- Browser `localStorage` for persistence
- GitHub Pages for hosting

## Run it locally

1. Clone the repo:
   ```bash
   git clone https://github.com/sunshiamathur/focus-log.git
   ```
2. Open `index.html` in your browser.

## What I learned

- Managing app state in plain JavaScript and keeping the UI in sync with it
- Persisting data with `localStorage` and handling the case where storage is unavailable
- Building a chart from scratch with CSS instead of a library
- Writing safer DOM code (using `textContent` rather than injecting user input as HTML)
- Supporting dark mode with CSS variables and `prefers-color-scheme`
- Deploying a static site with GitHub Pages

## Ideas for next steps

- [ ] Edit existing sessions
- [ ] Set a daily study goal and show progress
- [ ] Export sessions to CSV
- [ ] Break the code into separate HTML, CSS, and JS files
- [ ] Add tests for the time and chart calculations

## License

MIT
