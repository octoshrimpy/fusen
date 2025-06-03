# 🗂️ fusen

**fusen** (付箋) translates to a simple *sticky note* in Japanese — and that's exactly the idea.

A minimal, single-file, markdown-powered kanban board. Just drop it on GitHub Pages or your local machine and start organizing your thoughts. No build tools, no frameworks, no nonsense.

---

## ✨ Features

- 📝 Write your board in plain Markdown
- 🧠 Frontmatter-powered configuration
- 🧲 Drag and drop tasks between columns
- 🪶 Built with [Pico.css](https://picocss.com/) and Web Components
- 💾 Save to file — no backend needed
- 🧩 One HTML file, nothing else

---

## 📦 Usage

Write your kanban board like this:

```markdown
---
board-title: Personal Tasks
columns:
  - [🧊] Icebox
  - [🚧] In Progress
  - [✅] Done
---

- `[🧊]` Learn CSS
- `[🚧]` Build fusen
- `[✅]` Take a break
```

Then load it in `index.html`:

```html
<kanban-board src="board.md"></kanban-board>
```

---

## 🔧 Settings

Click the ⚙ icon to open the settings modal. Customize:

* Board title
* Column symbols
* Save-as name

---

## 🚀 Deploying

Just push to GitHub Pages or open the HTML file locally. That’s it.

---

## 🧘 Philosophy

**fusen** is about flow, not friction.
No logins, no databases, no yak shaving.

---

## 🛠️ Dev

Everything is in one file: `index.html`.

* Want to change how cards look? Edit the CSS.
* Want to parse different Markdown? Update the JS.
* Want to add new features? Keep it lean.

---

## 📄 License

MIT © octoshrimpy

---
