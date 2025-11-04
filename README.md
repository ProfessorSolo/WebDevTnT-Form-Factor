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

© 2025 Josh “Professor Solo” Solomon.  
Licensed under the PolyForm Education License 1.0.0.  
Use, modify, and share **for learning and teaching only**.  
Commercial or production use is not permitted.

---

> Part of **WebDev TnT — Web Development Tools & Techniques**  
> _Short demos that make the web go boom._
>
> p.s. > required fields are only half the story ⚡
