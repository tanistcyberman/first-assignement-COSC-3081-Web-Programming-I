# Lionel Messi - The Greatest of All Time

A multi-page website dedicated to Lionel Messi, built exclusively using pure HTML (HTML5 semantics) without CSS or JavaScript as part of **COSC 3081: Web Programming I (Chapter 2, Assignment 1)**.

---

## 📌 Project Overview

This website explores the career, records, and legacy of Lionel Andrés Messi. It adheres strictly to semantic HTML structure and W3C web standards.

### Features & Requirements Fulfillments:
- **HTML Only:** Zero CSS files, zero `<style>` tags, zero inline `style="..."` attributes, and zero JavaScript. Plain browser default styles.
- **Three Linked Pages:**
  - `index.html` - Homepage providing an introduction, early life, and career overview.
  - `pages/career.html` - Comprehensive senior club & international career statistics table (`border="1"`), records, and individual honors.
  - `pages/contact.html` - Fan registration form with semantic labels, email validation, required fields, and direct `mailto:` link.
- **Semantic Structure:** Every page contains `<header>`, `<nav>`, `<main>`, and `<footer>`.
- **Heading Hierarchy:** Strictly one `<h1>` per page, followed by properly ordered `<h2>` sections.
- **Lists & Tables:** Features ordered lists (`<ol>`), unordered lists (`<ul>`), and a structured statistical `<table>` with `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`, and `<th scope="...">`.
- **Multimedia Integration:** Embedded official 2022 FIFA World Cup Final highlights using standard HTML5 `<iframe>` (allowed by Chapter 2 rules).
- **Image Handling:** High quality images stored in the `images/` directory with descriptive `alt` attributes and verified relative file paths.
- **W3C Validated:** Tested against the Nu HTML Checker (`validator.w3.org`) with 0 errors.

---

## 📁 Repository Structure

```text
messi-website/
├── index.html
├── README.md
├── images/
│   ├── messi-action.jpg
│   └── messi-world-cup.jpg
└── pages/
    ├── career.html
    └── contact.html
```

---

## 🚀 Navigation & Local Testing

Open `index.html` in any web browser to view the website. All internal navigation links between the root directory and the `pages/` subfolder are fully relative and verified.
