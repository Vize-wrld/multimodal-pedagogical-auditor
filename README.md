# 🛠️ The Student Audit & Automation Ecosystem

A completely custom, modular automation ecosystem engineered to reverse-engineer curriculum design, map academic progress dynamically across a multi-term layout, and force rigorous engineering mastery through isolated testing loops.

---

## 📐 System Architecture Overview

This ecosystem is divided into three core pillars that operate collaboratively to automate and document the entire learning lifecycle:

### 1. The AI Pedagogical Audit Framework
An open-source prompt and analysis framework that acts as a strict, over-the-shoulder evaluator during active learning sessions.
* **Instructional Critique:** Reverse-engineers lecture delivery models, calculating cognitive load optimization and delivery precision metrics.
* **Scope-Bound Refactoring:** Intercepts technical concepts and provides optimized, clean, style-compliant refactoring patterns restricted strictly to a student's verified knowledge ceiling.
* **Session Report Generation:** Automatically outputs highly structured Markdown session reports containing raw core concepts, syntax exemplars, and localized tracking updates.

### 2. SyncEngine (Automation Dashboard)
The central nervous system and data-routing pipeline for the entire ecosystem.
* **Metadata & Syllabus Mapping:** Ingests comprehensive multi-term syllabus metadata (lesson names, numbers, paths) to feed a real-time progress-tracking dashboard.
* **NotebookLM Pipeline:** Targets and parses critical study points generated via NotebookLM, automatically extracting high-density notes and code snippets.
* **Cloud Synchronization:** Listens for the Auditor's Session Reports, seamlessly extracting, parsing, and appending documentation blocks into designated cloud storage environments without interrupting local development workflows.

### 3. The True Mastery AI (In Active Development)
An advanced, exclusive secondary framework planned to evolve into an expert programming mentor.
* **Isolated Testing Loops:** Designed to pull active logs from the primary session reports to compile bespoke, complex training scripts.
* **Rigorous Code Verification:** Engineered to replace passive reading by forcing manual, rigorous code compilation and execution testing.
* **Competency Validation:** Will generate custom-tailored, diagnostic study intervals, logging an official milestone only upon successful testing execution.

---

## 📂 Repository Directory

* [📁 docs/](/docs) — Architectural specifications and system documentation.
  * `ARCHITECTURE.md` — Core structural diagrams and pipeline breakdowns.
* [📁 frameworks/](/frameworks) — Prompts and scripts for core runtime logic.
  * `multimodal_pedagogical_auditor/` — Code, prompts, and data contracts (`system_instructions.md`, `SCHEMA_SPEC.md`).
  * `true_mastery_ai/` — Active dev space for the testing partner framework loops.
* [📁 sync_engine/](/sync_engine) — Application backend and tracking interface logic.
  * `automation_pipelines/` — Core Python daemons handling automated state serialization and automated NotebookLM/Google Drive ingestion pipelines.
  * `progress_dashboard/` — Custom dashboard data and tracking UI logic.

---

## 🚀 Tech Stack & Core Pipelines
* **Core Languages:** Python 3.x — Acts as the backbone execution environment for `SyncEngine`, executing local daemons to automatically parse terminal stdout JSON payloads, stream data, and handle file I/O operations.
* **Data Automation:** Programmatic pipeline interacting directly with the Gemini API, automated file-appending streams, and Google Drive cloud synchronization endpoints.
* **Prompt Engineering:** Multi-agent role prompting utilizing markdown schema isolation (`<notebooklm_notes>`, `<mastery_ledger>`).

---

## 📈 Long-Term Vision
Built out of a necessity to own, control, and secure an unassailable record of educational growth, this ecosystem treats the institutional curriculum as a raw data stream—ensuring that the student's personal development, portfolios, and tangible engineering capabilities remain completely independent, verifiable, and open-source.