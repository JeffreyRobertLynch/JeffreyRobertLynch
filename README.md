# Jeffrey Robert Lynch

## Applied AI Engineer | Production AI & Decision Support Systems | Evaluation & Deployment | LLM | RAG | HITL | XAI

AI/ML Systems Engineer focused on building end-to-end AI applications that integrate machine learning models into reliable, real-world systems.

Work includes LLM/RAG orchestration and evaluation pipelines, computer vision with explainability, and deployed AI applications with user-facing interfaces. Emphasis on structured outputs, reproducibility, and system-level design under practical constraints.

Projects below represent implementation and applied uses cases, with technical demos available in linked repositories.

> All publicly available projects are populated with public or dummy datasets for demo so as not to violate confidentiality.

---

## Featured AI/ML Systems

These projects demonstrate production-style AI/ML systems, including sanitized client work.

### 1. [StudioSync: LLM Decision Support & Evaluation System (demo)](https://github.com/JeffreyRobertLynch/StudioSync-HITL-Human-in-the-Loop-LLM-System-for-Narrative-Intelligence)
StudioSync was designed to automate batch evaluation of proposals to determine alignment with multi-criteria business priorities. Beyond decision support, it also functions as an automated model/task-fit evaluator due to the model-agnostic architecture.

> This project demonstrates systems and methodologies used in client engagements; the data has been modified for public demonstration. A complete technical demo is fully accessible in the README with structured outputs, batch evaluations, HITL-weighted leaderboards, and inference screenshots.

---

**Highlights:**

- **Generalizable Framework:** Extensible to healthcare ops, marketing, policy evaluation, proposal scoring, and any domain requiring priority alignment or resource allocation.
- **Model-Agnostic Orchestration:** Unified pipelines supporting local models (Qwen, Gemma, Llama) and cloud models (GPT, Claude, Gemini, Deepseek).
- **Complex Demo Use Case:** Ten high-quality cross-genre pitches and three divergent studio mandates designed to isolate granular **alignment fit** (Subgenres, Tone, Budget, Production Timeline, Audience Fit, etc.), instead of assessing general pitch quality alone.
- **Structured Scoring & Rationales:** Eight scored criteria with deterministic JSON output and concise (512 token) model-generated justifications. Structured model output populates analytics dashboards.
- **Custom Batch Evaluation:** Full matrix (models × mandates x pitches x HITL weights) producing sortable scores and leaderboards.
- **Human-in-the-Loop Weighting:** Adjustable section weights to customize user priorities with transparent raw output for interpretability and auditing.
- **Streamlit Interface:** For ingesting pitches/mandates, launching custom batch runs, inspecting raw output, analytics dashboards, and exporting final rankings.
- **Robust Pipelines:** Guarantees schema consistency across models and runs, enabling reliable scoring at scale. Run manager embeds metadata into all model outputs and system documents for traceability and reproducibility.

---

### 2. [GlassBox XAI: Medical Image Segmentation with Explainable AI & LLM Integration (demo)](https://github.com/JeffreyRobertLynch/GlassBox-XAI)
GlassBox is a high-performance solution to the standardized **ISIC 2018: Binary Segmentation** challenge dataset; performance metrics can be validly benchmarked vs. other solutions. The system's models segment medical images, accurately isolating potentially cancerous skin lesions within each image. Each model was designed to optimize specific metrics for specialized deployment concerns; error profiles are calculated and compared in detail. Additional constraints, beyond the standard challenge constraints, were introduced to address low-infrastructure deployment. Finally, multiple XAI (explainable AI) techniques were integrated into pipelines to address trust and regulatory compliance. 
 

> GlassBox has not undergone clinical validation and is not a medical device. All reported metrics reflect performance on a standardized test set and do not reflect or imply clinical validity. The system has never been deployed, but XAI techniques and pipelines have been repurposed in client work. Overview, metrics, model outputs, XAI visualizations, and research citations are fully accessible in the README for review.

---

**Highlights:** 
- **Variant Models:** Fine-tuned for specific error profiles (false positives vs. false negatives) via custom loss functions.
- **Realistic Constraints:** Achieved production-level performance benchmarks without pretrained models, ViTs, ensembles, or data beyond ISIC 2018.
- **Performance Metrics:** Dice: 0.8751 | IoU: 0.8000 | Precision: 0.9052 | Recall: 0.8870 | Accuracy: 0.9272 | F1 Score: 0.8751
- **Metrics-Driven Development:** using Dice, IoU, F1 score, and custom loss functions (Dice, Tversky, Hybrid).
- **Comprehensive XAI:** Including layer-wise Grad-CAM, saliency maps, integrated gradients, and pixel confidence maps.
- **Modular & Portable:** Pipelines for training, augmentation, evaluation, XAI tools, and preprocessing input images.
- **LLM Integration:** Chatbot interface for reliably querying and retrieving batch metrics. 
- **Multi-Domain AI/ML:** Computer Vision Segmentation, LLM for Retrieval-Augmented Generation (RAG), and Explainable AI (XAI) for transparency integrated for synergy in one system.

---

### 3. [LeafGuard: AI/ML Computer Version API (full repo)](https://github.com/JeffreyRobertLynch/leafguard-ai-cv)
LeafGuard demonstrates end-to-end AI/ML system delivery. It integrates CNN plant disease classification models into a FastAPI backend with an interactive HTML/CSS/JS GUI, allowing users to perform batch inference, visualize results, switch between models, generate confusion matrices, and download outputs Dockerized setup for production deployment. 

> Models are trained on lab datasets and are not intended for real-world use. Though simplified, this project demonstrates end-to-end AI/ML system engineering parallel to client work. Models and data required to run the application have been excluded. GUI screenshots and model outputs available in the README.

---

**Key Features:**
- **API Model Service:** Model serving, pipeline integration, multi-model management, GUI design, and API delivery.
- **End-to-End Deployment:** Complete pipeline from training notebook to prototype to model integration to API service to GUI to output analytics.
- **Model Flexibility:** Users can switch between multiple CNN models to compare performance or experiment with alternative architectures.
- **Actionable Outputs:** Batch classification results include color-coded disease heatmaps, test set metrics, confusion matrices, and downloadable visualizations.
- **Scalable Architecture:** Dockerized for easy deployment, reproducibility, and integration into larger AI/ML systems.
- **CNN Models:** Models used in this demo were trained on lab images for my senior CS capstone. They are accurate on the test set (99.4% binary accuracy, 94.5% 10-class accuracy) but would not be accurate in real-world conditions. However, it would be straightforward to train real-world accurate models and plug them into this system seamlessly due to modular design. I address this in the README. 

---

## Academic Projects with Honors - Software 2 & Technical Communication

### 4. [Customer Scheduling Management System](https://github.com/JeffreyRobertLynch/customer-scheduling-management-system)
A full-stack Java application designed to support global business scheduling and reporting. Featuring full CRUD functionality, dynamic report generation, and automated localization, this project highlights strong software engineering principles including MVC architecture, DAO pattern, and database connectivity.

> Full code present in public repo.

---

**Highlights:**  
- **Academic Excellence Award Recipient - Software 2: Advanced Java Concepts:** “Overall, the student's project submission is excellent in that it is an example of quality in work, considering the provided requirements. The backend is informative and organized, while the frontend is easy to use and functional. Excellent job!”
- **Full-Stack Software Engineering:** Full CRUD (Create, Read, Update, Delete), MCV + DAO with clear layer separation, mySQL integration.
- **Scale and Organization**: ~2000 lines of code across 40+ individual files with helper classes for translation, time zone adjustment, and automated alerts. 
- **Dynamic Localization:** All time zones and 15 Languages via keys and language bundles.
- **Security Features:** Password protection and user activity auditing.
- **Automated Reporting:** Integration of prepared SQL statements with Java functions. 
- **Object Oriented Programming:** Classes for data access objects and reports.

---

### 5. [Splunk Integration for Business Intelligence](https://github.com/JeffreyRobertLynch/Splunk-Integration-for-Business-Intelligence)
A comprehensive white paper and executive summary that demonstrates how Splunk can drive data-driven decision-making across Business Analytics, IT Infrastructure, and Cybersecurity Operations.

> White Paper & Executive Summary present in repo.

---

**Highlights:** 
- **Academic Excellence Award Recipient - Technical Communication:** “This submission shows excellence in its level of detail when describing [business case] and explaining how Splunk could help it attain greater success. Expert sources such as Vardhan (2021) provide conclusive information to support the claim that developing a better grasp of data will enable [business case] to create opportunities for expansion into underserved markets.”
- **Enterprise System Evaluation:** Assessed integration of Splunk into multiple business domains (Business Analytics, IT, Cybersecurity) with a focus on outcomes.
- **Business Case Development:** Created a business case focused operations efficiency, ROI, and security, aligned with the real-world value of Splunk.
- **Comprehensive Technical Writing:** Displayed proficiency at tailoring communication to diverse audiences, balancing complex details with high-level strategic recommendations.
- **Splunk Credits:** Earned 15 Splunk Credits during the research phase, showcasing hands-on expertise.

---

## Education

- **B.S. in Computer Science, ABET-Accredited Program** 
- **Stanford University: AI in Healthcare Specialization** 
- **DeepLearning.AI / Stanford University: Machine Learning Specialization** 
  - Supervised Machine Learning: Regression and Classification
  - Unsupervised Learning, Recommenders, Reinforcement Learning
  - Advanced Learning Algorithms
- **CompTIA Project+**, **Axelos ITIL v4**, **TEFL**, **Splunk**

---

## Contact

- [LinkedIn](https://www.linkedin.com/in/jeffrey-lynch-350930348)
- [GitHub](https://www.github.com/JeffreyRobertLynch)

Open to discussing AI/ML roles, collaborations, and applied AI work.
