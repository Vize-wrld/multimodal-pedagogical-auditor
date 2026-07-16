# 🧠 Multimodal Pedagogical Auditor

<p align="left">
  <img src="https://img.shields.io/badge/Status-Stable_Release-blue.svg" alt="Status" />
  <img src="https://img.shields.io/badge/Engine-Gemini_3.1_Flash_Live-orange.svg" alt="Engine" />
  <img src="https://img.shields.io/badge/Compliance-Strict_JSON_&_Markdown-brightgreen.svg" alt="Compliance" />
</p>

A high-performance, system-instructions framework designed for real-time and retrospective auditing of automated AI instructional streams. Optimized explicitly for the **Gemini 3.1 Flash Live** engine to evaluate teaching efficiency, monitor conceptual pacing, and enforce rigid data serialization constraints.

---

## 🚀 Core Capabilities
* **Dynamic Vision Anchoring:** Monitors visual timeline scrolling and real-time audio streams, adapting its critique based on UI state configurations.
* **Strict Schema Enforcement:** Guarantees standard Markdown report cards accompanied by a validated JSON payload for seamless, automated ingestion.
* **Zero-Inference Fallback:** Implements a rigid, non-hallucinating architecture that drops missing variables strictly to `"N/A"` or `null`.
* **Knowledge Boundary Synthesis:** Seamlessly integrates with external mastery logs to restrict pedagogical suggestions to a student's precise cumulative knowledge ceiling.

---

## 🛠️ Usage & Integration

### 1. The Metadata Override Protocol
To bypass visual extraction latency and ensure total baseline precision, initialize the auditing session by feeding the system a structured override block at the top of your prompt:

```text
[METADATA OVERRIDE]
Term: [e.g., Term 1]
Week: [e.g., Week 2]
Lesson Theme: [e.g., Core Automation Routing]
Course Track: [e.g., Software Engineering]
Course Name: [e.g., Python Architecture]
Course Code: [e.g., CS101]
Lesson Number: [e.g., Lesson 5]
Lesson Title: [e.g., Custom Pipeline Management]
```
### 2. Downstream Architecture Ingestion
At the conclusion of an instructional audit, invoke the compiler by triggering: `Generate Report`

The framework will generate an isolated report card terminating in a strictly validated JSON payload. Downstream pipelines (such as automated synchronization engines) read this block directly out of stdout to parse metrics and dynamically update long-term user logs without manual intervention.