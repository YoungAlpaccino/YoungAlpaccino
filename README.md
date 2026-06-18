<h1 align="center">Hi, I'm YoungAlpaccino 👋</h1>

<p align="center">
  <b>I build LLM tooling, ship full-stack AI products, and write the references I wish I'd had.</b>
</p>

<p align="center">
  <i>Python · FastAPI · React/TypeScript · LLM engineering</i>
</p>

---

Most of my work falls into three buckets: **tools people can install**, **products that actually run end-to-end**, and **references people actually use**. Here's the short tour.

<br/>

## 🚀 Shipped & installable

> Real packages, not demos. Tested, versioned, and on PyPI.

### [`llmbelt`](https://github.com/YoungAlpaccino/llmbelt) &nbsp; `pip install llmbelt`

[![PyPI](https://img.shields.io/pypi/v/llmbelt.svg)](https://pypi.org/project/llmbelt/)
[![CI](https://github.com/YoungAlpaccino/llmbelt/actions/workflows/ci.yml/badge.svg)](https://github.com/YoungAlpaccino/llmbelt/actions/workflows/ci.yml)
[![Python](https://img.shields.io/pypi/pyversions/llmbelt.svg)](https://pypi.org/project/llmbelt/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/YoungAlpaccino/llmbelt/blob/main/LICENSE)

A **zero-dependency** tool belt for working with LLMs — the small utilities you rewrite on every project, in one clean import: token counting & cost estimation, retry-with-backoff (sync **and** async), prompt templates, JSON extraction from model replies, conversation trimming, response caching, rate limiting, and RAG-ready text chunking.

- 🪶 **Pure standard library** — nothing to pull in, nothing to break.
- 🔌 **Provider-agnostic** — Anthropic, OpenAI, Gemini, anything.
- 🧪 **Fully tested** across Python 3.9 → 3.12, with CI on every push.

<br/>

## 🧩 Full-stack AI product — SiteCreator

> **Describe a website in one sentence, watch AI build it live.** An open-source prompt-to-site platform, shipped as two clean, independently-runnable repos — front-end and back-end. Runs free on a local model out of the box.

### [`simple-website-creator-frontend`](https://github.com/YoungAlpaccino/simple-website-creator-frontend) — the React app & live AI Builder

[![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)](https://vite.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-38BDF8?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/YoungAlpaccino/simple-website-creator-frontend/blob/main/LICENSE)

The UI: landing, auth, dashboard, and a **live Builder** that streams the generated page into a sandboxed `<iframe>` preview in real time. Edit-and-regenerate, one-click publish with a copyable link, JWT-guarded routes, and a single typed fetch client (`lib/api.ts`) that injects the token, normalizes errors, and parses the SSE generation stream. State managed with TanStack Query.

### [`simple-website-creator-backend-ai`](https://github.com/YoungAlpaccino/simple-website-creator-backend-ai) — the FastAPI service & AI engine

[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![SQLModel](https://img.shields.io/badge/SQLModel-7E56C2?logo=databricks&logoColor=white)](https://sqlmodel.tiangolo.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/YoungAlpaccino/simple-website-creator-backend-ai/blob/main/LICENSE)

The API: email + password auth (bcrypt + JWT), per-user project CRUD, and **AI generation streamed as Server-Sent Events**. The LLM layer is fully pluggable — **free by default on local Ollama**, swap to **Gemini / Groq / Claude** with one env var. Each site publishes to a clean public slug at `/p/{slug}`. SQLModel/SQLite out of the box, ready to point at Postgres for production.

<br/>

## 📚 References people actually use

> Dense, copy-pasteable, honest. Built to be skimmed and stolen from — not read cover to cover.

### [`python-cheatsheet`](https://github.com/YoungAlpaccino/python-cheatsheet) — Backend · AI · Embedded

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/YoungAlpaccino/python-cheatsheet/blob/main/LICENSE)
[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/)

The Python patterns you reach for daily across the three areas where people actually ship: **backend services** (FastAPI, async, SQLAlchemy, auth, Docker), **AI/ML** (NumPy, pandas, PyTorch, LLM APIs), and **embedded** (MicroPython, Pi GPIO, serial/I2C/SPI). No 40-page tutorials — just the snippets that save a Google search.

### [`llm-cheatsheets`](https://github.com/YoungAlpaccino/llm-cheatsheets) — Awesome LLM Engineering

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/YoungAlpaccino/llm-cheatsheets/blob/main/LICENSE)

A curated, **no-fluff** guide to building real applications with LLMs: hand-picked tools, frameworks, and runnable cheatsheets for API basics, prompt engineering, RAG, model selection, and cost/token management. Opinionated and maintained — every entry earns its place by helping you *ship* something.

<br/>

---

### 🛠️ Tech I reach for

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38BDF8?logo=tailwindcss&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?logo=vite&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)

<p align="center"><i>Tools that install, products that run, docs that help. ✦</i></p>
