# Hi, I'm kkj333 👋

AI engineer specializing in building systems with generative AI and LLMs.

---

## 🛠 Skills

### AI / ML
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Vertex AI](https://img.shields.io/badge/Vertex_AI-4285F4?style=flat&logo=google-cloud&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white)

**Core expertise**
- RAG / multi-agent systems / Text-to-SQL
- Prompt engineering / agent workflows
- Google Agent Developer Kit (ADK)

### Infrastructure
![Google Cloud](https://img.shields.io/badge/Google_Cloud-4285F4?style=flat&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

### Development
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

---

## 🌱 OSS Contributions

### [google/adk-python](https://github.com/google/adk-python)

**Issue #5539** — Discovered and reported an HTTP 500 error when ADK Developer UI creates sessions with Firestore-reserved `__session_metadata__` state keys. Filed a minimal reproduction, verified the fix in PR #5549, and contributed test guidance. Fixed (Close #5539).

https://github.com/google/adk-python/issues/5539

**PR #5640** — Fixed a bug where `list_sessions()` always returned `last_update_time` as `0.0`. Implemented timestamp conversion logic and added unit tests.

https://github.com/google/adk-python/pull/5640

**PR #5814** — Fixed `MissingGreenlet` when `DatabaseSessionService.append_event` runs with asyncpg. Read the revision field before commit and added a regression test. Integrated into `main`.

https://github.com/google/adk-python/pull/5814

**PR #5854** — Fixed a bug where `inline_data.display_name` was dropped when loading binary artifacts from `FileArtifactService` and `GcsArtifactService`. Persisted display names in file/GCS metadata and added regression tests. Integrated into `main`.

https://github.com/google/adk-python/pull/5854

**Issue #5799** — Reproduced and reported a bug where `FunctionTool` arguments typed as `Union[Pydantic, Pydantic]` were passed as plain dicts at runtime in ADK 2.0 GA. Fixed (Close #5799).

https://github.com/google/adk-python/issues/5799

## 🔗 Links

[![Zenn](https://img.shields.io/badge/Zenn-3EA8FF?style=flat&logo=zenn&logoColor=white)](https://zenn.dev/kkj)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/kkj333)
