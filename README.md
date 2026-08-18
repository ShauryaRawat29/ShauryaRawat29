# Hey, I'm Shaurya 👋

Final-year student working toward a career in ML / data engineering. I spend most of my time in Python — building backends, training models, and shipping things instead of leaving them in a notebook.

The thread that runs through my projects: **explainable AI**. If a model gives me an answer, I want to be able to say *why* it gave that answer. I try to carry that into everything I build.

## Projects

### QueryDocs — ask questions about your own documents
[Repo](https://github.com/ShauryaRawat29/querydocs)

Upload a PDF, TXT, Markdown or DOCX and ask questions about it. QueryDocs embeds the document into a FAISS index and answers only from what's actually in the file — every answer comes attached to the passages it used, so nothing gets made up.

It works with zero API keys out of the box (it falls back to returning the best-matching passages), and you can optionally add a Groq or OpenAI key for full sentence synthesis.

**Stack:** Python · FastAPI · sentence-transformers · FAISS · Next.js

### PhishGuard — phishing URL detection
[Repo](https://github.com/ShauryaRawat29/phishguard) · [Live demo](https://shauryarawat29.github.io/phishguard)

Paste a URL and it tells you whether it's phishing or legitimate — and why. An XGBoost model scores it on 33 hand-crafted URL features, then SHAP values show exactly which signals pushed the verdict. The server never actually visits the URL it's analyzing. This was my final-year minor project.

**Stack:** Python · XGBoost · SHAP · FastAPI · Docker · GitHub Pages + Render

### AI Essay Detector — evidence-based AI-writing analysis
[Repo](https://github.com/ShauryaRawat29/ai-essay-detector)

Instead of a binary "is this AI?" guess, it measures sentence-level statistical signals — perplexity, entropy, token probabilities — and compares them against human baselines. FastAPI + Next.js, built for the 2026 i12 HR Drive Hackathon, with 200+ tests.

**Stack:** Python · FastAPI · Next.js · statistical NLP

## Currently

Placement and internship season (2026) — open to software, ML and data engineering roles. When I'm not preparing for that, I'm extending QueryDocs or tinkering with smaller experiments.

## Tech

- **Python** — FastAPI, scikit-learn, XGBoost, SHAP, sentence embeddings, FAISS
- **JavaScript/TypeScript** — Next.js / React when a project needs a real UI
- **The rest** — SQL, Docker, Git + GitHub Actions, pytest, ruff

## Elsewhere

- GitHub: [ShauryaRawat29](https://github.com/ShauryaRawat29)
