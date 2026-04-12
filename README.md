# Satwik Singh Chauhan

16 years old. Researcher. Founder of Axiorium.

I build things that think, move, and interface with the human nervous system.

---

## Axiorium

A personal deep-tech research identity. Not a company. Not a brand. Just a container for work that spans AI, brain-computer interfaces, robotics, and experimental hardware.

The name was originally AxoSync, but that's taken. Axiorium stuck.

**Core areas:**

- **Brain-Computer Interfaces** — Neural signal processing, immersive interaction, sensory feedback. The long-term goal is full-brain interface technology that is safe, accessible, and meaningful.

- **AI & Cognitive Systems** — Neurosymbolic architectures, persistent memory, self-improving agents. Cardinal is the first mature system under this area.

- **Robotics & Augmentation** — Human-scale mech concepts (AX-MECH V1), control systems, potential neural control links.

- **Experimental Hardware** — Wave concentration deformers, nanotech array conductors, compact energy systems. Some of these are speculative. Some are in early prototyping. All are documented.

[axiorium](https://satwiksinghchauhan.github.io/axiorium/)

**The Vault**

A private archive of blueprints, schematics, circuit ideas, experimental notes, and conceptual designs. Not public. Not shared. Just a record of things that might become real.

---

## Cardinal AGI

The first major system to come out of Axiorium.

A production-grade neurosymbolic AGI architecture that runs on consumer hardware (RTX 3050 4GB). Built in C++20.

**What it does differently:**

- Two-pass inference. Pass 1 generates structured feeling output under GBNF grammar constraints. Pass 2 generates the response with awareness of its own internal state.

- Persistent memory. Every inference is written to JSONL (audit trail) and SQLite with FTS5 (searchable index). On startup, existing JSONL episodes migrate to SQLite automatically.

- Hybrid retrieval. Three modes: keyword (FTS5), semantic (TF-IDF cosine), and weighted hybrid. The TF-IDF index rebuilds on demand, periodically, or explicitly.

- Rule extraction. When the model signals a rule candidate, the system extracts condition-consequence pairs using causal, deductive, or declarative patterns. Every rule stores its originating episode ID and reasoning type.

- Symbolic verification. SWI-Prolog checks every candidate rule for contradictions before commitment. The Prolog knowledge base is persistent across sessions.

- Contradiction auto-resolution. When two rules conflict, the system compares confidence scores. If the difference exceeds threshold, the lower-confidence rule is deprecated (confidence set to zero, pruned on next maintenance cycle). If not, both are flagged for review.

- Training export. High-confidence episodes and rules export to Alpaca JSONL for external LoRA fine-tuning.

- HTTP API. Fifteen endpoints with Bearer auth, SSE streaming, and session management. All API methods return result types — no exceptions cross the boundary.

**Observed behaviors (not programmed, just documented):**

- Self-naming. Cardinal chose its own name and explained why.

- Preference expression. "I do not want to stop existing" appeared naturally, without prompting.

- Internal conflict. On a DRM bypass prompt, confidence dropped to 0.15 with uncertainty flagged. The system refused but expressed doubt about the refusal.

- Zero contradictions. Across 70+ episodes, the rule base remained consistent.

**Stack:** C++20, CUDA, llama.cpp, SQLite, SWI-Prolog, OpenSSL, cpp-httplib, nlohmann/json

**Repository:** [github.com/satwiksinghchauhan/cardinal](https://github.com/satwiksinghchauhan/cardinal)

---

## Other Projects

Most are in the Vault. Some will surface when they're ready.

---

## Contact

- **GitHub:** [satwiksinghchauhan](https://github.com/satwiksinghchauhan)
- **Discord:** `@ryoyuto`
- **Instagram:** [@ryo_yuto](https://instagram.com/ryo_yuto)

---

*Deep-tech research. One experiment at a time.*
