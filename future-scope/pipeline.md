# Future Roadmap: Macro-Auditing & Automation Pipeline

## 🔄 Tier 2: The Macro-Auditor (Systemic Amnesia Mitigation)
To address the "Lost in the Middle" phenomenon—where long-context models experience attention degradation across multi-hour instructional paths—the next architectural evolution splits auditing into a two-tiered system.

### Architecture Data Flow
* **Tier 1 (Active Micro-Auditor):** Captures high-fidelity local session metrics and outputs compressed, validated JSON payloads.
* **Tier 2 (Macro-Auditor Rollup):** An asynchronous process that ingests the accumulated historical JSON blocks from Tier 1. It synthesizes cross-session data to generate Weekly Meta-Analyses and Final Course Evaluations without hitting active API token limits.

## 🛠️ Automated Ingestion Pipeline
The manual extraction layer will be fully deprecated in favor of a programmatic Python pipeline interacting directly with the Gemini API backend.

[Local Session Audits] ──> (Python Script / Gemini API) ──> [Auto-Dump Local JSON]
│
▼
[Automated NotebookLM Ingestion] <── [Auto-Sync Google Drive] <── [Append Markdown Reports]

### Pipeline Technical Specifications
1. **Automated State Serialization:** Run local Python daemons to automatically parse, validate, and dump real-time session JSON logs into isolated directory pools.
2. **Cloud Synchronization:** Establish a local-to-cloud automated pipeline appending finalized Markdown evaluation report cards directly to target Google Drive endpoints.
3. **NotebookLM Scale Compliance:** Keep data representations tightly compressed to guarantee cumulative multi-session histories never exceed NotebookLM's 500,000-word / 200 MB per-source structural upper bounds.