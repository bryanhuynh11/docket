Docket

A Notion-style workspace for notes and tasks, built as a single HTML file.

Live site: https://bryanhuynh11.github.io/docket/

Features





Sign up and log in, with passwords salted and hashed (SHA-256)



Light and dark mode that follows your device and remembers your choice



Pages with a block editor: type / for headings, to-dos, lists, quotes, callouts and dividers



Markdown shortcuts: #, -, [], >, ---



Drag blocks to reorder them



Task board with Board (kanban) and Table views, plus status, priority, due date and tag



Search across pages and tasks with Ctrl K / ⌘K



Page icons and covers



Works on phones and desktops

How it works

Everything is in index.html: plain HTML, CSS and JavaScript, with no build step and no dependencies.

Accounts and data are saved in the browser's localStorage. This makes it a front-end demo of authentication, not a real backend: data stays in one browser on one device, and other people can't see your account.

Run it locally

Open index.html in any browser.

Credits

Built for TCSS 490 (Autumn 2026) with help from Claude.
