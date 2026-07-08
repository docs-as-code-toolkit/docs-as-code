# Docs-as-Code Toolkit
![Docs-as-Code](https://img.shields.io/badge/Docs--as--Code-Toolkit-blue)
> ![docs-as-code-toolkit-logo](https://docs-as-code-toolkit.github.io/docs-as-code/assets/logo/toolkit-logo_160.png)
>
> Part of the **Docs-as-Code Toolkit**  
> → [https://github.com/docs-as-code-toolkit](https://github.com/docs-as-code-toolkit)

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

It operates one layer above publishing: source documents, metadata, relations,
and review workflows remain the authoritative knowledge base; generated
documentation is a derived artifact. It can also be rendered and published by
docToolchain or similar tools, while this project's docs-toolbox provides the
necessary tools for local and CI-based rendering as well.

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

**architecture-knowledge-toolkit**
Reusable architecture knowledge structures:

* semantic contracts
* metadata conventions
* artifact templates
* traceability relations
* review workflows
* AI-assistable skills

👉 [Structure, relate, review, and evolve architecture knowledge](https://github.com/docs-as-code-toolkit/architecture-knowledge-toolkit).

---

**doc-generators** *(planned)*
Generate dynamic documentation:

* cross-links
* traceability
* architecture views

---

## Relationship to docToolchain

This project is not intended to compete with docToolchain.

[docToolchain](https://github.com/docToolchain) is a mature Docs-as-Code
toolchain for building, converting, publishing, and integrating technical and
software architecture documentation. The Docs-as-Code Toolkit focuses on the
layer above publishing: reproducible source workflows, structured architecture
knowledge, metadata, traceability, reviewability, and automation-friendly
conventions.

Both approaches can be combined. This toolkit can provide structured AsciiDoc
sources and metadata, while docToolchain or similar tools render and publish the
resulting documentation.

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
