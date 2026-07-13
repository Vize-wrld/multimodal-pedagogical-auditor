# Future Roadmap: Macro-Auditing & Automation Pipeline

## 🔄 Tier 2: The Macro-Auditor (Systemic Amnesia Mitigation)
To address the "Lost in the Middle" phenomenon—where long-context models experience attention degradation across multi-hour instructional paths—the next architectural evolution splits auditing into a two-tiered system.

### Architecture Data Flow
* **Tier 1 (Active Micro-Auditor):** Captures high-fidelity local session metrics and outputs compressed, validated JSON payloads.
* **Tier 2 (Macro-Auditor Rollup):** An asynchronous process that ingests the accumulated historical JSON blocks from Tier 1. It synthesizes cross-session data to generate Weekly Meta-Analyses and Final Course Evaluations without hitting active API token limits.

## 🛠️ Automated Ingestion Pipeline
The manual extraction layer will be fully deprecated in favor of a programmatic Python pipeline interacting directly with the Gemini API backend.