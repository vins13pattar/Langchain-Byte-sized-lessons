# Langchain---Byte-sized-lessons

A complete, **byte-sized interactive HTML course** covering the official [LangChain (Python) v1 documentation](https://docs.langchain.com/oss/python/langchain/overview). Built for developers who learn by doing — every concept gets a plain-language explanation, a memorable analogy, a minimal runnable example, a real-world use case, and a "gotchas" callout.

No build step, no server — open `index.html` in any browser.

## What's inside

- **32 lesson modules** across 8 parts: Getting Started → Core Components → Memory & State → Middleware → Advanced Patterns → Retrieval & RAG → Frontend → Build & Ship.
- **32 quizzes** (multiple-choice + interview questions) with instant scoring.
- **Beginner FAQ** (`faq.html`) — searchable answers to the questions newcomers hit most (install errors, the v0→v1 import confusion, "why isn't my tool called", memory, streaming, debugging).
- **Coverage checklist** (`checklist.html`) — every official doc page mapped to a module; the source of truth for completeness.
- **24 structural diagrams** in `/diagrams` as both `.svg` (rendered inline in each module) and editable `.excalidraw` files, labeled with real LangChain classes.

## Getting started

```bash
git clone https://github.com/vins13pattar/Langchain---Byte-sized-lessons.git
cd Langchain---Byte-sized-lessons
open index.html        # or just double-click it
```

Start at `index.html`, or jump straight into [`01-what-is-langchain.html`](01-what-is-langchain.html).

## Layout

```
index.html              Landing page + full module list
faq.html                Beginner FAQ (searchable)
checklist.html          Doc-coverage checklist (source of truth)
quiz-index.html         Quiz progress hub
NN-*.html               Lesson modules (01–32)
NN-quiz.html            Per-module quizzes
diagrams/               .svg + .excalidraw structural diagrams
```

## Accuracy

All code is verified against the live LangChain v1 docs. Canonical imports used throughout: `from langchain.agents import create_agent`, `from langchain.chat_models import init_chat_model`, `from langchain.agents.middleware import ...`. Deprecated v0 patterns (e.g. `create_react_agent`, `raise NodeInterrupt`) are intentionally avoided and called out in the FAQ.

---

Built against LangChain v1.0 · docs.langchain.com
