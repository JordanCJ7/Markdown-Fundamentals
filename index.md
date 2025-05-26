---
# 👇 Required front matter block to enable Jekyll processing
# This tells GitHub Pages to apply the selected theme's layout.
layout: default

# Optional: Sets the page title shown in the browser tab and theme header
title: Markdown Fundamentals
---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Markdown-Fundamentals](https://img.shields.io/badge/Guide-Markdown_Fundamentals-blue.svg)](https://github.com/JordanCJ7/Markdown-Fundamentals)

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

- [Quick Start Example](#quick-start-example)
- [Table of Contents](#table-of-contents)
- [How to Use This Repository](#how-to-use-this-repository)
- [Important Links](#important-links)
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
- [Accessibility Tips for Markdown](#accessibility-tips-for-markdown)
- [Common Pitfalls in Markdown](#common-pitfalls-in-markdown)
- [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq)
- [GitHub-Flavored Markdown (GFM)](#github-flavored-markdown)
- [Tools & Editors](#tools--editors)
- [Resources](#resources)
- [License](#license)

---

## 🎯 How to Use This Repository

This repository is designed to be a comprehensive guide to Markdown. Here’s how you can make the most of it:

- **🧑‍🎓 For Learners:**
  If you're new to Markdown, we recommend starting with the [Basic Syntax](#basic-syntax) section. Explore the examples and try them out yourself! You can also check out the [Tools & Editors](#tools--editors) section for software that can help you write and preview Markdown, and the [Resources](#resources) section for more learning materials.

- **🤝 For Contributors:**
  Contributions to this guide are welcome! If you'd like to add examples, improve explanations, or fix an error, please see our `CONTRIBUTING.md` file for guidelines.

- **🔍 For Those Looking for Specific Information:**
  Use the [Table of Contents](#table-of-contents) to quickly navigate to the information you need. Whether you're looking for details on [Advanced Syntax](#advanced-syntax), tips on [Accessibility](#accessibility-tips-for-markdown), or answers to [Frequently Asked Questions (FAQ)](#frequently-asked-questions-faq), the ToC can guide you there.

---

## 🔗 Important Links

For a better understanding of our project's guidelines and policies, please refer to the following documents:

- **[Contributing Guidelines](CONTRIBUTING.md):** Interested in contributing? Please see our Contributing Guidelines to get started.
- **[Code of Conduct](CODE_OF_CONDUCT.md):** We adhere to a Code of Conduct to ensure a welcoming and inclusive community for everyone.
- **[Security Policy](SECURITY.md):** Please review our Security Policy for reporting vulnerabilities and ensuring the safety of our project.

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
[Live Demo](https://markdownlivepreview.com/?text=%23%20H1%20%0A%23%23%20H2%0A%23%23%23%20H3%0A%23%23%23%23%20H4)

<details>
<summary>HTML Preview</summary>

```html
<h1>H1</h1>
<h2>H2</h2>
<h3>H3</h3>
<h4>H4</h4>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=This%20is%20one%20paragraph.%0A%0AThis%20is%20another.%0A%0ALine%20one.%20%20Line%20two.)

<details>
<summary>HTML Preview</summary>

```html
<p>This is one paragraph.</p>
<p>This is another.</p>
<p>Line one.<br>
Line two.</p>
```
</details>

**Preview:**
This is one paragraph.

This is another paragraph.

Line one.  
Line two (after two spaces).

### ✍ Emphasis

Use asterisks or underscores for emphasis. Single for *italic*, double for **bold**, triple for ***bold and italic***.

```markdown
*italic* or _italic_

**bold** or __bold__

***bold and italic***
```
[Live Demo](https://markdownlivepreview.com/?text=%2Aitalic%2A%20or%20_italic_%0A%0A%2A%2Abold%2A%2A%20or%20__bold__%0A%0A%2A%2A%2Abold%20and%20italic%2A%2A%2A)

<details>
<summary>HTML Preview</summary>

```html
<em>italic</em> or <em>italic</em>
<strong>bold</strong> or <strong>bold</strong>
<strong><em>bold and italic</em></strong>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=-%20Item%20A%0A-%20Item%20B%0A%20%20-%20Nested%20Item)

<details>
<summary>HTML Preview</summary>

```html
<ul>
  <li>Item A</li>
  <li>Item B
    <ul>
      <li>Nested Item</li>
    </ul>
  </li>
</ul>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=1.%20First%0A2.%20Second%0A3.%20Third)

<details>
<summary>HTML Preview</summary>

```html
<ol>
  <li>First</li>
  <li>Second</li>
  <li>Third</li>
</ol>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=%5BOpenAI%5D(https%3A%2F%2Fopenai.com)%0A%0A%3Chttps%3A%2F%2Fgithub.com%3E)

<details>
<summary>HTML Preview</summary>

```html
<a href="https://openai.com">OpenAI</a>
<a href="https://github.com">https://github.com</a>
```
</details>

**Preview:**
[OpenAI](https://openai.com)

<https://github.com>

### 🖼️ Images

Embed images using `![Alt Text](URL "Title")`. The alt text is important for accessibility.

```markdown
![Cute Cat](https://cdn2.thecatapi.com/images/MTY3ODIyMQ.jpg "Cute Cat")
```
[Live Demo](https://markdownlivepreview.com/?text=%21%5BCute%20Cat%5D(https%3A%2F%2Fcdn2.thecatapi.com%2Fimages%2FMTY3ODIyMQ.jpg%20%22Cute%20Cat%22))

<details>
<summary>HTML Preview</summary>

```html
<img src="https://cdn2.thecatapi.com/images/MTY3ODIyMQ.jpg" alt="Cute Cat" title="Cute Cat">
```
</details>

**Preview:**

![Cute Cat](https://cdn2.thecatapi.com/images/MTY3ODIyMQ.jpg "Cute Cat")

### 💬 Blockquotes

Use `>` to create blockquotes. You can include lists or other Markdown inside blockquotes.

```markdown
> This is a blockquote.
> 
> - Markdown is awesome
```
[Live Demo](https://markdownlivepreview.com/?text=%3E%20This%20is%20a%20blockquote.%0A%3E%20%0A%3E%20-%20Markdown%20is%20awesome)

<details>
<summary>HTML Preview</summary>

```html
<blockquote>
  <p>This is a blockquote.</p>
  <ul>
    <li>Markdown is awesome</li>
  </ul>
</blockquote>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=Use%20%60console.log()%60%20in%20JavaScript.)

<details>
<summary>HTML Preview</summary>

```html
Use <code>console.log()</code> in JavaScript.
```
</details>

**Preview:**
Use `console.log()` in JavaScript.

**Code block:**

<pre><code>```js
function hello() {
  console.log("Hello, Markdown!");
}
```</code></pre>
[Live Demo](https://markdownlivepreview.com/?text=%60%60%60js%0Afunction%20hello()%20%7B%0A%20%20console.log(%22Hello%2C%20Markdown!%22)%3B%0A%7D%0A%60%60%60)

<details>
<summary>HTML Preview</summary>

```html
<pre><code>function hello() {
  console.log("Hello, Markdown!");
}
</code></pre>
```
</details>

**Preview:**
```js
function hello() {
  console.log("Hello, Markdown!");
}
```

---

## 📈 Advanced Syntax

### 📊 Tables

Tables let you organize data in rows and columns. Use pipes (|) and dashes (-) to create tables.

```markdown
| Name    | Role      |
|---------|-----------|
| Alice   | Developer |
| Bob     | Designer  |
```
[Live Demo](https://markdownlivepreview.com/?text=%7C%20Name%20%20%20%20%7C%20Role%20%20%20%20%20%20%7C%0A%7C---------%7C-----------%7C%0A%7C%20Alice%20%20%20%7C%20Developer%20%7C%0A%7C%20Bob%20%20%20%20%7C%20Designer%20%20%7C)

<details>
<summary>HTML Preview</summary>

```html
<table>
  <thead>
    <tr><th>Name</th><th>Role</th></tr>
  </thead>
  <tbody>
    <tr><td>Alice</td><td>Developer</td></tr>
    <tr><td>Bob</td><td>Designer</td></tr>
  </tbody>
</table>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=-%20%5Bx%5D%20Install%20Git%0A-%20%5B%20%5D%20Learn%20Markdown%0A-%20%5B%20%5D%20Push%20to%20GitHub)

<details>
<summary>HTML Preview</summary>

```html
<ul>
  <li><input type="checkbox" checked disabled> Install Git</li>
  <li><input type="checkbox" disabled> Learn Markdown</li>
  <li><input type="checkbox" disabled> Push to GitHub</li>
</ul>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=Here%20is%20a%20footnote%20reference%5B%5E1%5D.%0A%0A%5B%5E1%5D%3A%20This%20is%20the%20footnote.)

<details>
<summary>HTML Preview</summary>

```html
<p>Here is a footnote reference<sup id="fnref1"><a href="#fn1" rel="footnote">1</a></sup>.</p>
<div class="footnotes">
  <ol>
    <li id="fn1">This is the footnote.</li>
  </ol>
</div>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=%3Cb%3EThis%20is%20bold%20using%20HTML%3C%2Fb%3E%0A%3Cdetails%3E%0A%20%20%3Csummary%3EClick%20to%20expand%3C%2Fsummary%3E%0A%20%20Hidden%20content%20here.%0A%3C%2Fdetails%3E)

<details>
<summary>HTML Preview</summary>

```html
<b>This is bold using HTML</b>
<details>
  <summary>Click to expand</summary>
  Hidden content here.
</details>
```
</details>

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
[Live Demo](https://markdownlivepreview.com/?text=%3Cdetails%3E%0A%20%20%3Csummary%3EMore%20Info%3C%2Fsummary%3E%0A%20%20You%20can%20hide%2Fshow%20content%20using%20this%20tag.%0A%3C%2Fdetails%3E)

<details>
<summary>HTML Preview</summary>

```html
<details>
  <summary>More Info</summary>
  You can hide/show content using this tag.
</details>
```
</details>

**Preview:**
<details>
  <summary>More Info</summary>
  You can hide/show content using this tag.
</details>

---

## ⚠️ Common Pitfalls in Markdown

Even experienced users can run into small issues with Markdown. Here are some common mistakes and how to avoid them:

- **Forgetting blank lines before/after lists or code blocks:**
  - Always leave a blank line before and after lists or code blocks to ensure they render correctly.
  - Example (incorrect):
    ```markdown
    Some text
    - Item 1
    - Item 2
    ```
  - Example (correct):
    ```markdown
    Some text

    - Item 1
    - Item 2
    ```
- **Not indenting nested lists properly:**
  - Use two spaces for each level of nesting.
- **Forgetting to close code blocks:**
  - Always use triple backticks (```) to open and close code blocks.
- **Incorrect link or image syntax:**
  - Make sure to use `[text](url)` for links and `![alt](url)` for images.
- **Using tabs instead of spaces:**
  - Some Markdown parsers may not handle tabs well; prefer spaces for indentation.

> **Tip:** If something doesn't render as expected, check for missing blank lines or incorrect syntax!

---

## ♿ Accessibility Tips for Markdown

Writing accessible Markdown ensures your content is usable by everyone, including people using screen readers or assistive technologies:

- **Use semantic headings:**
  - Structure your document with proper heading levels (`#`, `##`, `###`) to create a logical outline.
- **Add alt text to images:**
  - Always provide descriptive alt text in image syntax: `![Description](url)`.
- **Use meaningful link text:**
  - Avoid generic phrases like "click here"; instead, describe the link's destination.
- **Prefer lists for lists:**
  - Use Markdown list syntax for lists, not just plain text or dashes.
- **Keep tables simple:**
  - Use tables only for tabular data, and keep them easy to read.
- **Avoid using color alone for emphasis:**
  - Use bold or italics in addition to color to convey meaning.

> Good accessibility helps everyone!

---

## ❓ Frequently Asked Questions (FAQ)

**Q: How do I escape special characters in Markdown?**
- Use a backslash (`\`) before the character you want to escape. For example, to show a literal asterisk: `\*not italic\*` renders as \*not italic\*.

**Q: How do I add a table of contents?**
- You can manually create a table of contents using links to section headings. For example:
  ```markdown
  - [Introduction](#introduction)
  - [Usage](#usage)
  ```
  Most Markdown renderers (like GitHub) automatically generate anchor links for headings.

**Q: How do I add line breaks?**
- End a line with two spaces, or use a blank line to start a new paragraph.

**Q: Can I use HTML in Markdown?**
- Yes! Most Markdown parsers support inline HTML for advanced formatting.

**Q: How do I show raw Markdown (without rendering it)?**
- Wrap your Markdown in triple backticks (```) to create a code block, or use a single backtick for inline code.

**Q: Why isn't my list or code block rendering correctly?**
- Make sure you have blank lines before and after lists or code blocks, and use the correct indentation.

**Q: How do I add images with alt text?**
- Use: `![Alt text](image-url)`

**Q: How do I create checkboxes?**
- Use `- [ ]` for unchecked and `- [x]` for checked items in a list.

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
