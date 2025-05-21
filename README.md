# 📘 Markdown Fundamentals
---

A complete guide to **Markdown syntax** – from beginner to advanced. Whether you're writing documentation, READMEs, blog posts, or wikis, this repo will help you master Markdown formatting with real examples.

---

## ⚡ Quick Start Example

Here's a minimal Markdown example and how it looks when rendered:

This example shows a simple project README with a heading, a welcome message, a list, and a link. You can copy and paste this into any Markdown editor to see how it works.

```markdown
# My Project

Welcome to my project!

- Easy to use
- Fast
- Open source

[Learn more](https://spec.commonmark.org/)
```

When rendered, it will look like this:

# My Project

Welcome to my project!

- Easy to use
- Fast
- Open source

[Learn more](https://spec.commonmark.org/)

---

## 📂 Table of Contents

- [What is Markdown?](#what-is-markdown)
- [Getting Started](#getting-started)
- [Basic Syntax](#basic-syntax)
  - [Headings](#headings)
  - [Paragraphs & Line Breaks](#paragraphs--line-breaks)
  - [Emphasis](#emphasis)
  - [Lists](#lists)
  - [Links](#links)
  - [Images](#images)
  - [Blockquotes](#blockquotes)
  - [Code](#code)
- [Advanced Syntax](#advanced-syntax)
  - [Tables](#tables)
  - [Task Lists](#task-lists)
  - [Footnotes](#footnotes)
  - [HTML in Markdown](#html-in-markdown)
  - [Collapsible Sections](#collapsible-sections)
- [GitHub-Flavored Markdown (GFM)](#github-flavored-markdown)
- [Tools & Editors](#tools--editors)
- [Resources](#resources)
- [License](#license)

---

## 📖 What is Markdown?

**Markdown** is a lightweight markup language used to format plain text. It’s widely used in:

- GitHub READMEs
- Technical documentation
- Static site generators (like Jekyll, Hugo)
- Note-taking apps (like Obsidian, Notion)

---

## 🚀 Getting Started

To write Markdown:
- Use any plain text editor (`.md` file)
- Or try online editors like [Dillinger](https://dillinger.io/) or [StackEdit](https://stackedit.io/)

---

## 🧱 Basic Syntax

### 🔠 Headings

Use headings to organize your content. The number of `#` symbols indicates the heading level (from H1 to H4).

```markdown
# H1 
## H2
### H3
#### H4
```

**Preview:**
# H1
## H2
### H3
#### H4

### 📄 Paragraphs & Line Breaks

Separate paragraphs with blank lines. Add two spaces at the end of a line to create a line break.

```markdown
This is one paragraph.

This is another.

Line one.  Line two.
```

**Preview:**

This is one paragraph.

This is another (After enter).

Line one.  
Line two (after two spaces).

### ✍ Emphasis

Use asterisks or underscores for emphasis. Single for *italic*, double for **bold**, triple for ***bold and italic***.

```markdown
*italic* or _italic_

**bold** or __bold__

***bold and italic***
```

**Preview:**

*italic* or _italic_

**bold** or __bold__

***bold and italic***

### 🔢 Lists

Create unordered lists with dashes or asterisks, and ordered lists with numbers. Indent for nested lists.

**Unordered:**
```markdown
- Item A
- Item B
  - Nested Item
```
**Preview:**
- Item A
- Item B
  - Nested Item

**Ordered:**
```markdown
1. First
2. Second
3. Third
```
**Preview:**
1. First
2. Second
3. Third

### 🔗 Links

Add links using `[text](URL)`. You can also paste a URL directly to create an automatic link.

```markdown
[OpenAI](https://openai.com)

<https://github.com>
```
**Preview:**

[OpenAI](https://openai.com)

<https://github.com>

### 🖼️ Images

Embed images using `![Alt Text](URL "Title")`. The alt text is important for accessibility.

```markdown
![Alt Text](https://via.placeholder.com/150 "Image Title")
```
**Preview:**

![Alt Text](https://via.placeholder.com/150 "Image Title")

### 💬 Blockquotes

Use `>` to create blockquotes. You can include lists or other Markdown inside blockquotes.

```markdown
> This is a blockquote.
> 
> - Markdown is awesome
```
**Preview:**

> This is a blockquote.
> 
> - Markdown is awesome

### 💻 Code

Show inline code with backticks (\`). For code blocks, use triple backticks and specify the language for syntax highlighting.

**Inline code:**
```markdown
Use `console.log()` in JavaScript.
```
**Preview:**

Use `console.log()` in JavaScript.

**Code block:**
```markdown
```js
function hello() {
  console.log("Hello, Markdown!");
}
```
```
**Preview:**
```js
function hello() {
  console.log("Hello, Markdown!");
}
```

### 📊 Tables

Tables let you organize data in rows and columns. Use pipes (|) and dashes (-) to create tables.

```markdown
| Name    | Role      |
|---------|-----------|
| Alice   | Developer |
| Bob     | Designer  |
```
**Preview:**
| Name    | Role      |
|---------|-----------|
| Alice   | Developer |
| Bob     | Designer  |

### ✅ Task Lists

Task lists are checkboxes you can use for to-do items or project tracking. Use `- [ ]` for unchecked and `- [x]` for checked items.

```markdown
- [x] Install Git
- [ ] Learn Markdown
- [ ] Push to GitHub
```
**Preview:**
- [x] Install Git
- [ ] Learn Markdown
- [ ] Push to GitHub

### 🧷 Footnotes

Footnotes let you add references or extra notes. Use `[^1]` in the text and define the note at the bottom.

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote.
```
**Preview:**
Here is a footnote reference[^1].

[^1]: This is the footnote.

### 🧱 HTML in Markdown

You can use raw HTML for advanced formatting or features not supported by Markdown.

```markdown
<b>This is bold using HTML</b>
<details>
  <summary>Click to expand</summary>
  Hidden content here.
</details>
```
**Preview:**
<b>This is bold using HTML</b>
<details>
  <summary>Click to expand</summary>
  Hidden content here.
</details>

### 🔽 Collapsible Sections

Collapsible sections let you hide and show content. Use the `<details>` and `<summary>` HTML tags.

```markdown
<details>
  <summary>More Info</summary>
  You can hide/show content using this tag.
</details>
```
**Preview:**
<details>
  <summary>More Info</summary>
  You can hide/show content using this tag.
</details>

---

## 🧬 GitHub-Flavored Markdown

GitHub-Flavored Markdown (GFM) adds extra features like syntax highlighting, task lists, tables, emojis, and mentions.

* Syntax highlighting for code blocks
* Task lists for project management
* Tables for structured data
* Emojis: `:sparkles:` → ✨
* Mentions: `@user`, `#issue`, etc.

---

## 🛠️ Tools & Editors

Here are some popular tools and editors for writing and previewing Markdown:

* [Dillinger](https://dillinger.io/) – Online Markdown editor
* [Obsidian](https://obsidian.md/) – Note-taking app with Markdown support
* [Typora](https://typora.io/) – Minimal Markdown editor
* [VSCode](https://code.visualstudio.com/) with Markdown Preview
* [Markdown Live Preview](https://markdownlivepreview.com/) – Online live preview

---

## 📚 Resources

Helpful resources for learning more about Markdown:

* [CommonMark Spec](https://spec.commonmark.org/) – The official Markdown specification
* [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/) – GitHub's Markdown documentation
* [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/) – Quick reference for Markdown syntax

---

## 📜 License

This project is licensed under the MIT License.
Feel free to fork, use, and share!

---

> 💡 *Contributions are welcome! Feel free to open issues or submit PRs.*

