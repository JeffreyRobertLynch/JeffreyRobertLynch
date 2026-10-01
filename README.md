# Jeffrey Robert Lynch

## Applied AI Engineer | AI Systems | Evaluation | LLMs | Computer Vision | XAI

Applied AI engineer focused on building and evaluating end-to-end AI systems that turn ambiguous problems into working, measurable software.

I build across LLM orchestration, evaluation harnesses, computer vision, explainability, model serving, and full-stack AI applications with an emphasis on structured outputs, reproducibility, traceability, practical constraints, and measurable alignment with project goals.

The projects below demonstrate three complementary capabilities: **AI evaluation & decision support, technically rigorous AI/ML development, and end-to-end AI application delivery.**

> All featured systems use public or sanitized data. Live execution with reproducible results is available upon request.

---

# Featured AI/ML Systems

## 1. [StudioSync: LLM Decision Support & Evaluation System](https://github.com/JeffreyRobertLynch/StudioSync-HITL-Human-in-the-Loop-LLM-System-for-Narrative-Intelligence)

StudioSync automates batch evaluation of proposals to determine alignment with configurable multi-criteria business priorities defined by users. 

Beyond decision support, it also functions as an automated model/task-fit evaluation harness due to the model-agnostic architecture. Multiple discrete models can be tested, scored, and compared on the exact same task to determine suitability.

### Highlights

- **Generalizable Evaluation Framework:** Extensible to healthcare ops, marketing, policy evaluation, proposal scoring, and domains requiring multi-criteria priority alignment or resource allocation.
- **Model-Agnostic Orchestration:** Unified pipelines support local and cloud LLMs, including Qwen, Gemma, Llama, DeepSeek, GPT, Claude, and Gemini.
- **Multi-Dimensional Evaluation:** Evaluates proposals against explicit user-defined priorities with customizable weights, including: budget, production timeline, and audience fit.
- **Structured Outputs:** Deterministic JSON schemas parse raw output into machine-readable scores with concise model-generated rationales.
- **Batch Evaluation:** Models × mandates × proposals can be evaluated in repeatable matrix runs, producing sortable scores and comparative leaderboards.
- **Human-in-the-Loop:** Adjustable criterion weights allow users to change priorities while preserving transparent scoring and raw model outputs.
- **Traceability & Reproducibility:** Run metadata, system documents, model information, and structured outputs provide a reproducible evaluation trail.
- **Interactive Interface:** Streamlit application supports data ingestion, batch execution, raw-output inspection, analytics, and result export.

**Methodology, golden set design, structured outputs, evaluation results, dashboards, and implementation details are available in the repository.**

---

## 2. [GlassBox: Computer Vision Segmentation, Evaluation & XAI](https://github.com/JeffreyRobertLynch/GlassBox-XAI)

GlassBox is a from-scratch computer-vision segmentation system built in adherence to the standardized **ISIC 2018 Binary Segmentation** challenge dataset, focused on highlighting potentially cancerous skin lesions for decision support. Performance metrics can be validly benchmarked vs. other solutions.

The system uses three specialized model variants optimized for different error profiles and evaluates them using a common global-pixel evaluation baseline. Multiple XAI pipelines provide additional visibility into model behavior.

> GlassBox is a research/demo system and is not a medical device or clinically validated system. Results below reflect performance on the standardized test set.

### Evaluation Results

| Model | Accuracy | Dice / F1 | IoU | Precision | Recall |
|---|---:|---:|---:|---:|---:|
| Precision-Optimized | **92.72%** | 86.44% | 76.11% | **90.28%** | 82.91% |
| Balance-Optimized | 92.67% | **86.74%** | **76.58%** | 87.87% | 85.64% |
| Recall-Optimized | 91.82% | 85.95% | 75.37% | 82.80% | **89.36%** |

### Highlights

- **Three Specialized Models:** Separate models optimized for minimizing false negatives, minimizing false positives, and balanced performance provide measurable error-profile tradeoffs.
- **From-Scratch Architecture:** Custom U-Net architecture trained without pretrained models, ViTs, ensembles, or external data.
- **Custom Loss Functions:** Dice, Tversky, and hybrid loss functions produce specialized segmentation behavior.
- **Quantitative Evaluation:** Custom metric functions calculate globally aggregated TP, TN, FP, and FN counts across the complete test set for consistent comparison.
- **Comprehensive XAI:** Layer-wise Grad-CAM, saliency maps, integrated gradients, and pixel-confidence visualizations provide multiple views of model behavior.
- **Practical Constraints:** CPU-Optimized inference and compute-light architecture support portability and wide deployment.
- **LLM Integration:** Structured interface for querying and retrieving evaluation metrics.
- **Modular Pipelines:** Separate training, preprocessing, evaluation, augmentation, and XAI components support reuse across computer-vision systems.

**Methodology, confusion matrices, metrics, visualizations, implementation details, and research references are available in the repository.**

---

## 3. [LeafGuard: End-to-End AI/ML Computer Vision API](https://github.com/JeffreyRobertLynch/leafguard-ai-cv)

LeafGuard demonstrates complete delivery of multiple AI models as a usable software service.

CNN classification models are integrated into a FastAPI backend with an interactive web interface supporting batch inference, model switching, visualization, evaluation, and downloadable results.

### Highlights

- **Model Serving:** CNN inference integrated into a modular FastAPI service.
- **End-to-End Delivery:** Model training -> model integration -> inference pipeline -> API -> GUI -> analytics/output.
- **Model Switching:** Multiple models can be loaded and compared through the same application architecture.
- **Batch Inference:** Process multiple images and generate structured classification results.
- **Evaluation Outputs:** Confusion matrices, test-set metrics, and visual result summaries are integrated into the application.
- **Interactive Interface:** HTML/CSS/JavaScript GUI provides model selection, inference, visualization, and result export.
- **Containerized Deployment:** Dockerized architecture supports reproducible setup and integration into larger systems.

The demonstration models use laboratory datasets and are not intended for real-world deployment. The architecture is designed to allow models to be replaced without rebuilding the surrounding application.

**Full implementation, architecture, screenshots, and system outputs are available in the repository.**

---

# Academic Projects with Honors

## 4. [Customer Scheduling Management System](https://github.com/JeffreyRobertLynch/customer-scheduling-management-system)

A full-stack Java/SQL CRUD application for global business scheduling, reporting, and user management.

- **Academic Excellence Award Recipient - Software 2: Advanced Java Concepts:** “Overall, the student's project submission is excellent in that it is an example of quality in work, considering the provided requirements. The backend is informative and organized, while the frontend is easy to use and functional. Excellent job!”
- **Full-Stack Engineering:** MVC + DAO architecture, CRUD operations, MySQL integration, and clear separation of application layers.
- **Application Features:** Dynamic reporting, automated alerts, activity auditing, authentication, and database-backed workflows.
- **Automated Reporting:** Integration of prepared SQL statements for one click report generation.
- **Internationalization:** 15 languages and automated time-zone handling using reusable localization infrastructure.
- **Scale:** Approximately 2,000 lines of code across 40+ files.

**Full implementation available in the repository.**

---

## 5. [Splunk Integration for Business Intelligence](https://github.com/JeffreyRobertLynch/Splunk-Integration-for-Business-Intelligence)

A technical white paper and executive summary examining how Splunk can support data-driven decision-making across business analytics, IT infrastructure, and cybersecurity.

- **Academic Excellence Award Recipient - Technical Communication:** “This submission shows excellence in its level of detail when describing [business case] and explaining how Splunk could help it attain greater success. Expert sources such as [cited research] provide conclusive information to support the claim that developing a better grasp of data will enable [business case] to create opportunities for expansion into underserved markets.”
- **Enterprise System Evaluation:** Examined applications across multiple operational domains.
- **Business Case Development:** Connected technical capabilities to operational efficiency, ROI, and security considerations.
- **Technical Communication:** Translated complex technical concepts into structured recommendations for business audiences.
- **Splunk:** Earned 15 Splunk Credits during the research phase.

**White paper and executive summary available in the repository.**

---

# Education

- **B.S. in Computer Science — ABET-Accredited Program**
- **Stanford University: AI in Healthcare Specialization**
- **DeepLearning.AI / Stanford University: Machine Learning Specialization**
  - Supervised Machine Learning: Regression and Classification
  - Advanced Learning Algorithms
  - Unsupervised Learning, Recommenders, Reinforcement Learning
- **CompTIA Project+**
- **Axelos ITIL v4**
- **TEFL**
- **Splunk**

---

# Contact

- [LinkedIn](https://www.linkedin.com/in/jeffrey-lynch-350930348)
- [GitHub](https://www.github.com/JeffreyRobertLynch)

Open to discussing Applied AI, AI/ML systems, evaluation, and engineering opportunities.
