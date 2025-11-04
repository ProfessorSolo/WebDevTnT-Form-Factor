# 💥 WebDev TnT — Lesson 02: Form Factor — HTML Forms that Feel Right

**Topic:** Modern HTML Forms and Progressive Enhancement  
**Focus:** Structure, semantics, validation, accessibility, and the new 2025 pseudo-classes.

---

Welcome to **Form Factor**, a staged exploration of modern HTML forms.  
Each demo stage reveals one new element or concept — progressing from a single text field to a full, accessible form.  
The goal: build understanding, not boilerplate.

---

## ⚡ What It Demonstrates

- Form semantics — `<form>`, `<label>`, `<fieldset>`, `<legend>`
- Input types — `text`, `email`, `password`, `checkbox`, `radio`, `select`, `textarea`
- HTML5 constraint validation (`required`, `pattern`, etc.)
- Focus and accessibility with `:focus-visible` and `.visually-hidden`
- The **new 2025** `:user-valid` / `:user-invalid` pseudo-classes for friendlier validation

---

## 🧭 Quick Start

```bash
git clone https://github.com/ProfessorSolo/WebDevTnT-Form-Factor.git
cd WebDevTnT-Form-Factor
```

Then open **`form-factor.html`** with a local server (for example, VS Code’s _Live Server_ extension) and use the dropdown to explore stages of the form demo.

---

## 🧪 Try This

1. Add a new input type (`url`, `tel`, etc.) and test its built-in validation.
2. Comment out `novalidate` and observe how constraint validation behaves.
3. Modify focus colors using `:focus-visible` in the stylesheet.
4. Toggle the `.visually-hidden` label utility and run a screen reader test.

---

## 🧰 Tech Stack

- **HTML5** — semantic structure and accessible markup
- **CSS3** — layout, gradients, shadows, and animation
- **JavaScript (vanilla)** — interactivity and progressive enhancement

All demos run directly in the browser — no frameworks, no build tools.

---

## 🧱 Folder Structure

```
form-factor/
├── form-factor.html
├── README-form-factor.md
│
├── styles/
│   ├── reset.css
│   ├── brand.css
│   └── form-factor.css
│
└── scripts/
    └── formFactor.js
```

---

## 🧩 Linked Stylesheets (order matters)

```html
<link rel="stylesheet" href="./styles/reset.css" />
<link rel="stylesheet" href="./styles/brand.css" />
<link rel="stylesheet" href="./styles/form-factor.css" />
```

### Optional Fonts

```html
<link rel="preconnect" href="https://fonts.googleapis.com" />
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
<link
  href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&family=JetBrains+Mono:wght@400;600&display=swap"
  rel="stylesheet"
/>
```

---

## 🔒 License

WebDevTnT Learner License 1.0 (WebDevTnT-LEARN-1.0)

Copyright © 2025 Joshua Solomon (Professor Solo) 

Permission is hereby granted, free of charge, to students and independent learners to use, copy, and modify this material solely for personal study and skill development, subject to the following conditions:

Authorized Use Only
Use is limited to individual, non-commercial learning. This material may not be used, copied, or modified for teaching, training, workshops, or any group instruction, whether free or paid.

No Redistribution
You may not publicly share, publish, or repost this material or any derivative works online, in print, or as part of any other project or repository.

No Commercial Use
Commercial use, sublicensing, or sale of this material or any derivative is strictly prohibited.

Attribution
You must retain this copyright notice and the author attribution in all personal copies and derivative works.

Integrity Clause
The names “WebDevTnT” and “Professor Solo” may not be used to endorse or promote any work derived from this material.

Warranty Disclaimer
THIS MATERIAL IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NONINFRINGEMENT.

When in doubt: learn from it — don’t teach from it.

SPDX-License-Identifier: WebDevTnT-LEARN-1.0

---

> Part of **WebDev TnT — Web Development Tools & Techniques**  
> _Short demos that make the web go boom._
>
> p.s. > required fields are only half the story ⚡
