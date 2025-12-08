# Jeffrey Robert Lynch

## AI/ML Systems Engineer | Full-Stack AI Systems | LLM & CV | XAI & HITL | Communicator

I build and communicate explainable, high-performance AI systems across computer vision and LLMs, with a focus on transparency, human-AI collaboration, and real-world deployment.

---

- [LinkedIn](https://www.linkedin.com/in/jeffrey-lynch-350930348)
- [GitHub](https://www.github.com/JeffreyRobertLynch)

---

## Featured Projects

### 1. [StudioSync HITL: Model-Agnostic LLM Evaluation Engine](https://github.com/JeffreyRobertLynch/StudioSync-HITL-Human-in-the-Loop-LLM-System-for-Narrative-Intelligence)
StudioSync is a fully custom, model-agnostic LLM evaluation system that scores cross-genre TV series pitches against diverse studio mandates. It uses engineered pitches, structured rubrics, unified system prompting, and deterministic JSON/CSV/Markdown parsing to benchmark alignment across multiple models (local and API). The system demonstrates strong orchestration, output reliability, evaluation design, and human-in-the-loop integration.

> Full code and methodology are not publicly available to protect intellectual property. A complete technical demo is fully accessible in the README with structured outputs, batch evaluations, HITL-weighted leaderboards, and inference screenshots.

---

**Key Features:**

- **Model-Agnostic Orchestration:** Unified interface powering Qwen3:8b (local), GPT-4o, Claude 3.5 Sonnet, and Gemini 1.5 Pro with interchangeable prompts and schemas.
- **Engineered Pitch & Mandate Framework:** Ten high-quality cross-genre pitches and three divergent studio mandates designed to isolate granular **alignment fit** (Subgenres, Tone, Budget, Production Timeline, Audience Fit, etc.), instead of assessing creative quality alone.
- **Structured Scoring & Rationales:** Eight scored criteria with deterministic JSON output and concise model-generated justifications.
- **Batch Evaluation Engine:** Full 4x10×3 matrix (models × mandates x pitches) producing sortable scores and leaderboards.
- **Human-in-the-Loop Weighting:** Adjustable scoring weights with transparent raw output for interpretability and bias control.
- **Streamlit Interface:** For loading pitches, selecting models, launching batch runs, inspecting raw output, and exporting final rankings.
- **Robust Parsing Pipeline:** Guarantees schema consistency across models and runs, enabling reliable scoring at scale.

---

**Highlights:**

- **Model-Agnostic Systems Engineering:** Unified orchestration across four LLM families with structured prompts, standardized outputs, and consistent evaluation logic.
- **Evaluation Design & Alignment Modeling:** Custom rubric and engineered dataset enabling real alignment assessment rather than subjective “pitch quality” scoring.
- **Deterministic Output Handling:** JSON parsing, error correction, HITL weighting, and leaderboard generation built for reliability, scalability, and reproducibility.
- **Human-in-the-Loop Transparency:** Raw structured outputs visible pre-weighting for traceability and control by decision-makers.
- **Generalizable Framework:** Extensible to healthcare ops, marketing, policy evaluation, proposal scoring, and any domain requiring priority alignment or resource allocation.
- **End-to-End Architecture:** Full working system with multi-model support, scalable batch execution, interactive UI, and polished demo.
- **Practical Application:** A high-impact example of applying LLMs not for “chat” but for **domain-constrained evaluation**, alignment modeling, and orchestration engineering.

---

### 2. [GlassBox XAI: Attention U-Net for Medical Image Segmentation with Explainability](https://github.com/JeffreyRobertLynch/GlassBox-XAI)
GlassBox is a high-performance medical image segmentation system built from scratch using a custom U-Net with attention mechanisms, trained on the ISIC 2018 skin lesion dataset. It features three variant models with performance trade-offs and a comprehensive XAI suite for clinical trust and regulatory compliance. Computational complexity is low for the achieved metrics, XAI techniques, and local LLM integration, making it ideal for low infrastructure deployments.

> Full code and methodology are not publicly available to protect intellectual property. Overview, metrics, model outputs, XAI visualizations, and research citations are fully accessible in the README for review.

---

**Key Features:**
- **Variant Models:** Fine-tuned for different error profiles (false positives vs. false negatives) via custom loss functions.
- **Realistic Constraints:** Achieved production-level performance benchmarks without pretrained models, ViTs, ensembling, or data beyond ISIC 2018.
- **Performance Metrics:** Dice: 0.8751 | IoU: 0.8000 | Precision: 0.9052 | Recall: 0.8870 | Accuracy: 0.9272 | F1 Score: 0.8751
- **XAI Tools:** Including layer-wise Grad-CAM, saliency maps, integrated gradients, pixel confidence maps, and confusion matrices.
- **Modular & Portable:** Pipelines for training, augmentation, evaluatation, XAI tools, and preprocessing input images.
- **Comprehensive Demos:** For both technical and non-technical audiences, showcasing system performance and interpretability.
- **LLM Integration:** For reliably querying batch metrics, using Tinyllama with hard-coded scaffolding. 

---

**Highlights:**  
- **Multi-Domain AI/ML:** Medical Image Segmentation with Computer Vision, NLP/LLM, and Explainable AI (XAI) integrated for synergy.
- **High-performance Segmentation:** with custom architecture, fine-tuning with custom loss functions, and robust evaluation.
- **Comprehensive XAI:** Robust application of techniques for interpretability, transparency, and regulatory compliance.
- **Metrics-Driven Development:** using Dice, IoU, F1 score, and custom loss functions (Dice, Tversky, Hybrid).
- **Exploration and Documentation:** of performance trade-offs via optimizing variant models for specialized goals.
- **Scalable and Portable:** Modular, reproducible, and generalizable workflows for efficient deployment and iteration.
- **Thoroughness:** Extensive research, experimentation, and domain-aware development to address real-world challenges.

---

### 3. [LeafGuard AI: CNN-Based Plant Disease Classification Web Application](https://github.com/JeffreyRobertLynch/leafguard-ai-cv)
LeafGuard is a CNN-based plant disease classifier web application (FastAPI) trained on the Tomato Leaf Disease Detection dataset. It achieves 99.4% accuracy (binary disease detection) and 94.5% accuracy (multiclassification) across 10 disease classes. Includes batch image processing, color-coded visualizations for actionable monitoring, model switching for scalability, and Dockerized setup for production deployment. 

> Full code present in public repo, from notebook training to FastAPI deployment. Models and data required to run the application have been excluded. GUI screenshots and model output images available in the README.

---

**Key Features:**
- **Full AI/ML Application:** Frontend and backend integrated with trained models running in hard-coded functions to provide real-time outputs.
- **Test Accuracy:** 99.4% accuracy (binary disease detection); 94.5% accuracy (multiclassification) across 10 disease classes.
- **Batch Classification:** Classifies a 24-image batch in under 2 seconds (local), generating confidence scores and batch visualization.
- **Real-World Utility:** Color-coded prediction maps for flagging diseased plants by location to enable actionable disease monitoring.
- **Additional Features:** Includes model switching, image downloads, and user feedback submission to support future training iterations.
- **User-Generated Evaluation:** Generate accuracy scores and confusion matrices for any loaded model with optional PNG downloads.

---

**Highlights:**  
- **Production:** Includes well-structured requirements.txt, tested Dockerfile, docstrings, and README to support collaboration, iteration, and production deployment.
- **End-to-End Development:** From data to model training to app integration to dockerized deployment.
- **Scalable Architecture:** High-throughput batch processing to handle larger datasets and integration of future models.
- **Custom GUI:** Actionable visual output for easy decision-making and real-time disease monitoring.
- **Full Lifecycle:** From initial academic prototype project to deployed AI/ML web application.

---

### 4. [Customer Scheduling Management System](https://github.com/JeffreyRobertLynch/customer-scheduling-management-system)
A full-stack Java application designed to support global business scheduling and reporting. Featuring full CRUD functionality, dynamic report generation, and automated localization, this project highlights strong software engineering principles including MVC architecture, DAO pattern, and security.

> Full code present in public repo.

---

**Key Features:**
- **Full-Stack Java Application:** MVC + DAO pattern with clear layer separation and mySQL database connectivity.
- **Scale and Organization**: ~2000 lines of code across 40+ individual files with helper functions for translation, time zone adjustment, and automated alerts. 
- **Automated Localization:** All time zones & 15 languages.
- **Security Features:** Password protection and user activity auditing.

---

**Highlights:**  
- **Academic Excellence Award Recipient - Software 2: Advanced Java Concepts:** “Overall, the student's project submission is excellent in that it is an example of quality in work, considering the provided requirements. The backend is informative and organized, while the frontend is easy to use and functional. Excellent job!”
- **Full-Stack Software Engineering:** Full CRUD (Create, Read, Update, Delete), MCV + DAO, mySQL integration.
- **Dynamic Localization:** All time zones and 15 Languages via keys and language bundles.
- **Automated Reporting:** Integrtion of prepared SQL statements with Java functions. 
- **Object Oriented Programming:** Classes for data access objects and reports.

---

### 5. [Splunk Integration for Business Intelligence](https://github.com/JeffreyRobertLynch/Splunk-Integration-for-Business-Intelligence)
A comprehensive white paper and executive summary that demonstrates how Splunk can drive data-driven decision-making across Business Analytics, IT Infrastructure, and Cybersecurity Operations.

---

**Highlights:** 
- **Academic Excellence Award Recipient - Technical Communication:** “This submission shows excellence in its level of detail when describing [business case] and explaining how Splunk could help it attain greater success. Expert sources such as Vardhan (2021) provide conclusive information to support the claim that developing a better grasp of data will enable [business case] to create opportunities for expansion into underserved markets.”
- **Enterprise System Evaluation:** Assessed and integrated Splunk into multiple business domains (Business Analytics, IT, Cybersecurity).
- **Business Case Development:** Created a business case focused operations efficiency, ROI, and security, aligned with the real-world value of Splunk.
- **Comprehensive Technical Writing:** Displayed proficiency at tailoring communication to diverse audiences, balancing complex details with high-level strategic recommendations.
- **Splunk Credits:** Earned 15 Splunk Credits during the research phase, showcasing hands-on expertise.

---

## Certifications & Education

- **B.S. in Computer Science, ABET-Accredited Program** 
- **Stanford University: AI in Healthcare Specialization** 
- **DeepLearning.AI / Stanford University: Machine Learning Specialization** 
  - Supervised Machine Learning: Regression and Classification
  - Unsupervised Learning, Recommenders, Reinforcement Learning
  - Advanced Learning Algorithms
- **CompTIA Project+**, **Axelos ITIL v4**, **TEFL**, **Splunk**

---
