# Dr. Katharina Jacoby
### Emergency Physician and Systems Engineer

I am a physician who builds software and automation tools, writes about AI ethics, and studies the gaps between discrete and continuous systems—whether in topology, language, or clinical reasoning. I fix things—sometimes with code, sometimes with adrenaline. My work spans **clinical systems engineering** (small, auditable tools that fit into existing workflows, prioritizing safety, transparency, and local-first design), **AI ethics** (the silent drift of contextual contamination, the philosophical right to hesitate before automating judgment), **Mathematics and Computational Physics** (how epistemic violence in translations erases depth and rigor; finite-size effects and grid artifacts in twisted lattices). Across all of it, the same principle holds: **don't flatten ambiguity and depth.**

---

## 🛠️ Software Projects

### **Advice-Only Pipeline with Local LLM **
*Python • scikit-learn • FastAPI • SQLite • MIMIC-IV*
A decoupled architecture for real-time, interpretable risk predictions.
- **Features:** CatBoost models for risk prediction, and fully local/in-memory processing.
- **Safety:** Advice-only outputs (human approval required), full audit trails, and configurable probability thresholds.
- **Status:** Core pipeline functional.

### **Heilmittel Assistent / BVBChecker**
*Python/FastAPI → Windows .exe (PyInstaller)*
A local rules application for ICD-10 eligibility checks.
- **Features:** Runs entirely offline with no data storage; ships with installer scripts for easy deployment.
- **Status:** Core engine complete
- 
### **Medical T5 Mini**
*Hugging Face T5-small • DataCollator • Beam Search*
A debugging-driven fine-tuning project for educational purposes.
- **Achievement:** Solved a "True"-only output bug via systematic isolation (task prefixing, pipeline cleaning).
- **Lesson:** Applying clinical diagnostic rigor to ML debugging—rule out causes one by one.

---

## 📚 Publications & Research

### **Pattern Recognition in Discrete Twisted Lattices**
*A Descriptive Study of Scaling Behavior and Finite-Size Effects*
- **Repository:** [discrete-twisted-lattices-patterns](https://github.com/KatharinaJacoby/discrete-twisted-lattices-patterns)
- **Summary:** A numerical study of finite-size effects in non-orientable surfaces (Twisted Torus & Klein Bottle). Documents the correction of "perfect" constant artifacts and the discovery of a robust $\lfloor L/2 \rfloor$ scaling law.
- **Includes:** Formal manuscript and a **Non-Math Folk Guide** explaining the grid, the glitch, and the geometry.

### **AI Ethics & Philosophy**
- **[Contextual Contamination: The Silent Drift of Large Language Models via Stored Conversation Data](https://github.com/KatharinaJacoby/AI_ethics/blob/main/Contextual%20Contamination-%20The%20Silent%20Drift%20of%20Large%20Language%20Models%20via%20Stored%20Conversation%20Data.md)**
  - An analysis of how stored conversation data subtly alters model behavior over time.
- **[The Right to Hesitate](https://github.com/KatharinaJacoby/AI_ethics/blob/main/The%20Right%20to%20Hesitate.md)**
  - A philosophical argument for preserving human deliberation in automated decision-making systems.

### **Historical Mathematics & Philology**
- **[Zhu Shijie's Work on Algebra](https://github.com/KatharinaJacoby/Zhu-Shijie)**
  - A philological critique of translation erasure in classical Chinese algebra, arguing that standard translations obscure the rigorous "dimension" and "critique" in Zhu Shijie's 14th-century masterpiece.

### **Technical Guides**
- **[LLM Fine-Tuning Debugging Guide](https://github.com/KatharinaJacoby/LLM-Fine-tuning-Debugging-Guide)**
  - A practical guide to diagnosing and fixing common fine-tuning failures, applying clinical diagnostic methods to machine learning.

---

## 🌐 Online Presence & Portfolio

- **Publications:** [PhilPeople Profile](https://philpeople.org/profiles/katharina-jacoby/publications)
- **Hugging Face:** [katharina112](https://discuss.huggingface.co/u/katharina112/summary)
- **Kaggle:** [kjacoby](https://www.kaggle.com/kjacoby)
- **Open Source Badges:** [![Holopin Badges](https://holopin.me/katharinajacoby)](https://holopin.io/@katharinajacoby)

---

## 🤝 Collaboration & Contact

I am open to collaborating on:
- Open-source non-profit automation
- Local/offline tools for resource-limited settings
- Reproducible, ethical automation
- Discussing Ethics, Mathematics and Computational Physics

**Contact:** k.jacoby at posteo.de

> *"The future of healthcare isn't about replacing professionals with technology. It's about giving them better tools—built together, for everyone."*

---

### ⚠️ AI Training Opt-Out
This repository is **excluded from all AI training datasets** under [GitHub's DMCA policy](https://docs.github.com/en/site-policy/content-removal-policies/dmca-takedown-policy). Violations will be reported.
