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

### 📄 Paragraphs & Line Breaks

* Paragraphs are separated by blank lines.
* Add two spaces at end of a line for a line break.

```markdown
This is one paragraph.

This is another.

Line one.  
Line two (after two spaces).
```

### ✍ Emphasis

Use asterisks or underscores for emphasis. Single for *italic*, double for **bold**, triple for ***bold and italic***.

```markdown
*italic* or _italic_

**bold** or __bold__

***bold and italic***
```

### 🔢 Lists

Create unordered lists with dashes or asterisks, and ordered lists with numbers. Indent for nested lists.

**Unordered:**

```markdown
- Item A
- Item B
  - Nested Item
```

**Ordered:**

```markdown
1. First
2. Second
3. Third
```

### 🔗 Links

Add links using `[text](URL)`. You can also paste a URL directly to create an automatic link.

```markdown
[OpenAI](https://openai.com)

<https://github.com>
```

### 🖼️ Images

Embed images using `![Alt Text](URL "Title")`. The alt text is important for accessibility.

```markdown
![Alt Text](https://via.placeholder.com/150 "Image Title")
```

### 💬 Blockquotes

Use `>` to create blockquotes. You can include lists or other Markdown inside blockquotes.

```markdown
> This is a blockquote.
> 
> - Markdown is awesome
```

### 💻 Code

Show inline code with backticks (\`). For code blocks, use triple backticks and specify the language for syntax highlighting.

**Inline code:**

```markdown
Use `console.log()` in JavaScript.
```

**Code block:**

<pre>
```js
function hello() {
  console.log("Hello, Markdown!");
}
```
</pre>

---

## 🚀 Advanced Syntax

### 📊 Tables

```markdown
| Name    | Role      |
|---------|-----------|
| Alice   | Developer |
| Bob     | Designer  |
```

### ✅ Task Lists

```markdown
- [x] Install Git
- [ ] Learn Markdown
- [ ] Push to GitHub
```

### 🧷 Footnotes

```markdown
Here is a footnote reference[^1].

[^1]: This is the footnote.
```

### 🧱 HTML in Markdown

```markdown
<b>This is bold using HTML</b>
<details>
  <summary>Click to expand</summary>
  Hidden content here.
</details>
```

### 🔽 Collapsible Sections

```markdown
<details>
  <summary>More Info</summary>
  You can hide/show content using this tag.
</details>
```

---

## 🧬 GitHub-Flavored Markdown

GitHub supports **GFM**, which includes:

* Syntax highlighting
* Task lists
* Tables
* Emojis: `:sparkles:` → ✨
* Mentions: `@user`, `#issue`, etc.

---

## 🛠️ Tools & Editors

* [Dillinger](https://dillinger.io/)
* [Obsidian](https://obsidian.md/)
* [Typora](https://typora.io/)
* [VSCode](https://code.visualstudio.com/) with Markdown Preview
* [Markdown Live Preview](https://markdownlivepreview.com/)

---

## 📚 Resources

* [CommonMark Spec](https://spec.commonmark.org/)
* [GitHub Markdown Guide](https://guides.github.com/features/mastering-markdown/)
* [Markdown Cheatsheet](https://www.markdownguide.org/cheat-sheet/)

---

## 📜 License

This project is licensed under the MIT License.
Feel free to fork, use, and share!

---

> 💡 *Contributions are welcome! Feel free to open issues or submit PRs.*

