# MedMosaic

A student-created space where human sciences, biology, medicine, chemistry, and compassion come together. Explore clear explanations, fun facts, medical processes, personal learning experiences, and creative projects — all designed to make science more understandable, meaningful, approachable, and human.

---

## How This Site Works (No Programming Required!)

This website is built with **Jekyll** and hosted free on **GitHub Pages**. You **never** need to write code — you just write articles in plain Markdown (like writing notes with some simple formatting).

### What is Markdown?

Markdown is a simple way to format text. Here's everything you need:

```markdown
# Big heading
## Section heading
### Smaller heading

Regular paragraph text. Just type normally.

**Bold text** and *italic text*.

- Bullet point
- Another bullet

1. Numbered item
2. Another item

> A quote or callout box

[Link text](https://example.com)
```

That's it! If you can write a text message, you can write Markdown.

---

## How to Add a New Article (Directly on GitHub — No Downloads Needed!)

You do everything in your web browser at github.com. No software to install.

### Step 1: Create a file on GitHub

1. Go to your repository on GitHub.
2. Click the `_articles` folder.
3. Click **"Add file"** → **"Create new file"**.
4. In the file name box at the top, type your article name with hyphens and `.md` at the end:
   - `how-the-heart-works.md`
   - `what-is-dna.md`
   - `first-aid-burns.md`

### Step 2: Copy this template into your file

```markdown
---
title: "Your Article Title Here"
date: 2026-08-15
category: Biology
description: >
  One or two sentences describing what this article is about.
disclaimer: true
sources:
  - name: "Source Name"
    description: "What this source covers."
    url: "https://example.com/link-to-source"
  - name: "Another Source"
    description: "What this source covers."
    url: "https://example.com/another-link"
---

Write your introduction paragraph here.

## First Section

Your content here. Use **bold** for important terms.

## Second Section

More content. Use bullet points:

- Point one
- Point two
- Point three

## Remember This

Wrap up your article with key takeaways.
```

### Step 3: Fill in the top section (front matter)

| Field | What to write |
|-------|---------------|
| `title` | Your article's title in quotes |
| `date` | Today's date: `2026-08-15` format |
| `category` | Pick one: `First Aid`, `Biology`, `Medicine`, `Chemistry`, `Anatomy`, `Nutrition`, `Mental Health` |
| `description` | 1-2 sentence summary |
| `disclaimer` | Set to `true` for health/medical articles, `false` for others |
| `sources` | List your references (copy the format above) |

### Step 4: Write your article below the `---`

Just write! Use `##` for section headings, `**bold**` for key terms, `-` for bullet lists.

### Step 5: Save ("Commit")

1. Scroll down to the green **"Commit changes"** button.
2. Type a short message like "Add article about burns".
3. Click **"Commit changes"**.

Done! The site rebuilds automatically in ~1 minute. No terminal, no git commands, nothing else to do.

---

## Callout Boxes (Tips, Warnings, etc.)

Use `>` (blockquote) to create highlighted boxes:

```markdown
> **ℹ️ Note:** This is an informational callout.

> **⚠️ Important:** This is a warning.

> **🚨 Emergency:** This is urgent information.

> **💡 Tip:** This is a helpful tip.
```

---

## Enabling Comments

Readers can ask questions on every article using GitHub-powered comments. One-time setup:

1. Go to [utteranc.es](https://utteranc.es) and install the app on your repo.
2. In `_config.yml`, change `comments: repo:` from `"OWNER/AZ-MedMosaic"` to your actual GitHub username/repo.

---

## Publishing to GitHub Pages

1. Push all files to the `main` branch.
2. Go to repo **Settings → Pages**.
3. Under "Source", select `main` branch, `/ (root)` folder.
4. Wait ~1 minute. Your site will be live at `https://your-username.github.io/AZ-MedMosaic/`.

---

## File Structure

```
AZ-MedMosaic/
├── _config.yml          ← Site settings (title, URL, etc.)
├── _articles/           ← YOUR ARTICLES GO HERE (just .md files!)
│   └── coughing-or-choking.md
├── _layouts/            ← Page templates (don't need to edit)
│   ├── default.html
│   └── article.html
├── assets/css/style.css ← Styling (don't need to edit)
├── index.html           ← Homepage (auto-lists your articles)
├── search.html          ← Search page (works automatically)
├── about.md             ← About page (edit if you want)
├── Gemfile              ← Dependencies (don't touch)
└── README.md            ← This file
```

**The only folder you ever need to touch is `_articles/`** — just add `.md` files there and the site handles everything else automatically.

---

## Quick Reference

| I want to... | Do this on github.com |
|---|---|
| Add an article | Go to `_articles/` → Add file → Create new file |
| Edit an article | Click the `.md` file → pencil icon ✏️ → edit → Commit |
| Fix a typo | Same as edit — click the file, click pencil, fix it, commit |
| Change the site title | Edit `_config.yml` → change `title:` line |
| Add a topic/category | Just use a new category name in your article's front matter |
| Enable comments | Edit `_config.yml` → change `comments: repo:` to your repo |
| See my site | Go to `https://your-username.github.io/AZ-MedMosaic/` |

---

## License

Content is for educational purposes. Not a substitute for professional medical advice.
