**Emergency Physician → Clinical Systems Engineer**

---
### 👩‍⚕️💻 About Me
I’m an **emergency physician** who builds **software and automation tools** to address real-world clinical problems.
As a **Clinical Systems Engineer**, I focus on:
- **Small, auditable tools** (FastAPI, SQLite, scikit-learn) that fit into existing workflows.
- **Safety, transparency, and rollback paths**—patient care always comes first.
- **Local-first design** (no cloud dependencies, no unnecessary data sharing).
- **Advice-only systems**—augmenting clinical work, never replacing judgment.

> *"I don’t build AI for healthcare. I build tools for healthcare professionals—where it adds real value."*

---
### 🛠️ Projects
#### Advice-Only Pipeline with Local LLM & SPC Monitoring
*Python • scikit-learn • FastAPI • SQLite • MIMIC-IV*

- **CatBoost Models**: provides real-time, interpretable risk predictions to support clinician decision-making.
- **SPC Monitoring**: Shewhart/EWMA for real-time performance tracking (review prompts only)
- **Decoupled Architecture**: Prediction pipeline + separate LLM assistant service
- **Local-Only**: No cloud, no stored data - in-memory processing with JSONL audit logs

**Key Features**:
✅ Advice-only outputs (human approval required)
✅ Full audit trails for all system interactions
✅ Configurable probability thresholds
✅ Monthly SPC baseline updates

**Status:**
Core pipeline functional

---
#### Heilmittel Assistent / BVBChecker
*Python/FastAPI → Windows .exe (PyInstaller)*

A **local rules app** for ICD-10 eligibility checks:
- Runs offline, no data stored, ships with installer scripts.
- **Status:** Core engine done; pilot testing next.

---
#### Medical T5 Mini
*Hugging Face T5-small • DataCollator • Beam Search*

Debugging-driven fine-tuning:
- Solved a "True"-only bug via systematic isolation (task prefixing, pipeline cleaning).
- **Lesson:** Debugging ML like a physician—rule out causes one by one.
- **Notebook:** [Kaggle](https://www.kaggle.com)

---
### 🧭 Clinical Systems Engineering
I use the term **Clinical Systems Engineer** because:
- **"Clinical"** means starting with real healthcare problems.
- **"Systems"** means focusing on entire workflows, not just models or apps.
- **"Engineer"** means writing code, designing tools, and fixing bugs.

> *"Most healthcare tech is built by engineers who don’t understand clinics—or clinicians who don’t build. I do both."*

---
### 🎓 Methodology
I apply **clinical problem-solving** to technical systems:
1. Start with the problem, not the tool.
2. Diagnose bugs like a clinician: data, model, or deployment?
3. No black boxes—if we can’t explain it, it’s not ready.
4. Test safely: shadow deployments and A/B tests, like clinical trials.

---
### 🤝 Collaboration
I’m open to collaborating on:
- Open-source non-profit automation
- Local/offline tools for resource-limited settings
- Reproducible, ethical automation

---

**Contact:**
[Email](k.jacoby at posteo.de)


**Find my work:**

- [Kaggle](https://www.kaggle.com)
- [Hugging Face](https://discuss.huggingface.co)

---
### 🏆 Open Source
I contribute to open-source projects that make a real difference.
[![Holopin Badges](https://holopin.me/katharinajacoby)](https://holopin.io/@katharinajacoby)

---
> *"The future of healthcare isn’t about replacing professionals with technology. It’s about giving them better tools—built together, for everyone."*
