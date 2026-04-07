![Docs-as-Code](https://img.shields.io/badge/Docs--as--Code-Toolkit-blue)
![Docker](https://img.shields.io/badge/Docker-ready-blue)

<div style="display: flex; gap: 1rem; flex-wrap: wrap">
<img src="https://docs-as-code-toolkit.github.io/docs-as-code/assets/logo/toolkit-logo_160.png"/>
<h1>Docs-as-Code Toolkit</h1>
</div>

> Build documentation like software.
>
>Versioned. Reproducible. Automated.

---

## 🎯 What this is

This is not just a collection of repositories.

It’s a **complete Docs-as-Code ecosystem** that helps you:

* eliminate "works on my machine"
* unify local and CI environments
* structure and connect architecture documentation
* treat documentation as a **first-class artifact**

---

## 🧩 The Toolkit

### 🔧 Infrastructure

**docs-toolbox**
A Docker image with everything you need:

* Asciidoctor
* Pandoc
* Graphviz
* ...

👉 [Run the same environment locally and in CI](https://github.com/docs-as-code-toolkit/docs-toolbox).

---

### 🎨 Presentation

**asciidoc-style** *(coming soon)*
Reusable styling for:

* architecture documentation
* websites
* CVs

---

### 🧠 Automation

**doc-generators** *(planned)*
Generate dynamic documentation:

* cross-links
* traceability
* architecture views

---

### 🌐 Example / Showcase

**profile**
Real-world usage of the toolkit:

* personal website
* CV generation
* architecture documentation

👉 [Profile of Dieter Baier](https://github.com/dieterbaier/profile).

---

## 🧭 Philosophy

> Write once. Publish everywhere.

Documentation should be:

* ✔ versioned
* ✔ testable
* ✔ reproducible
* ✔ automatable

---

## 🚀 Getting started

Run your documentation build inside a reproducible environment:

```bash
docker run --rm \
  -v $(pwd):/app \
  -w /app \
  ghcr.io/docs-as-code-toolkit/docs-toolbox:latest \
  asciidoctor -v
```

---

## 💬 Discussions

Have questions, ideas, or feedback?

👉 Use the **Discussions** tab to:

* ask questions
* share ideas
* show how you use the toolkit

---

## 🤝 Why this matters

Documentation is often:

* outdated
* inconsistent
* hard to maintain

This approach turns it into something that actually scales.

---

## 👤 Author

Created by [Dieter Baier](https://github.com/dieterbaier)
Software Architect · Docs-as-Code enthusiast
