# Jeffrey Robert Lynch

## AI/ML Systems Engineer | Educator | Ethical AI | NLP/LLM | Computer Vision | XAI | HITL

I build and communicate explainable, high-performance AI systems across computer vision and LLMs, with a focus on transparency, human-AI collaboration, and real-world deployment.

## Let’s Connect

- [LinkedIn](https://www.linkedin.com/in/jeffrey-lynch-350930348)
- [GitHub](https://www.github.com/JeffreyRobertLynch)

---

## Featured Projects

### 1. [GlassBox XAI: Attention U-Net for Medical Image Segmentation with Explainability Suite](https://github.com/JeffreyRobertLynch/GlassBox-XAI)
GlassBox is a high-performance medical image segmentation system built from scratch using a custom U-Net with attention mechanisms, trained on the ISIC 2018 skin lesion dataset. It features three variant models with performance trade-offs and a comprehensive XAI suite for clinical trust and regulatory compliance. Computational complexity is relatrively low for the achieved metrics, making it ideal for low infrastructure deployments like rural areas.

> Full code and methodology are not publicly available to protect intellectual property. Demos, metrics, model outputs, and XAI visualizations are fully accessible in the README for review.

---

**Key Features:**
- Three variant models fine-tuned for different error profiles (false positives vs. false negatives) via custom loss functions.
- Achieved production-level performance benchmarks without pretrained models, ViTs, ensembling, or data beyond ISIC 2018.
- Performance metrics: Dice: 0.8751 | IoU: 0.8000 | Precision: 0.9028 | Recall: 0.8291 | Accuracy: 0.9272 | F1 Score: 0.8644
- XAI tools: Layerwise Grad-CAM, saliency maps, integrated gradients, pixel confidence maps, and confusion matrices.
- Modular image processing pipeline for augmenting training data and preprocessing test images.
- Comprehensive demo for both technical and non-technical audiences, showcasing system performance and interpretability.

---

**Highlights:**  
- High-performance medical image segmentation with a custom architecture and significant development constraints.
- Comprehensive application of XAI techniques for interpretability, transparency, and regulatory compliance.
- Advanced metrics-driven development using Dice, IoU, F1 score, and custom loss functions (Dice, Tversky, Hybrid).
- Exploration of performance trade-offs via optimizing variant models for specialized goals.
- Modular, reproducible, and generalizable workflow for efficient deployment.
- Extensive research, experimentation, and domain-aware development to address real-world challenges.

---

### 2. [StudioSync HITL: Human-in-the-Loop LLM System for Narrative Intelligence](https://github.com/JeffreyRobertLynch/StudioSync-HITL-Human-in-the-Loop-LLM-System-for-Narrative-Intelligence)
**Note**: *Updating use case to reflect migration from GPT-4 to GPT-5 for LLM component.*
- Built an **HITL system** for human-led creative development using **studio design docs** and **RAG**.  
- **Automated evaluation** of concepts, episodes, and seasons for continuity, tone & narrative DNA. 
- **Demonstrated use case** by supporting development of a chaotic ensemble TV series **across all phases**: studio pitch, writers’ room, rough scripts, table read feedback, to finalized season 1. 
- **Prioritized human creativity** by adhering to **Human-First, Human-Last** design principles.

---

**Highlights:**  
- **Flagship Project: LLM / NLP + HITL Systems**
- **Cross-Disciplinary HFHL (Human-First, Human-Last) HITL System Design**
- **Short-Form (Pitch, Outline, Beat Sheet) and Long-Form (Episode, Season, Full Corpus) Evaluation and Feedback**
- **Guided by Human-Authored Documents for Tone, Style, Structure, Rule Adherence, Alignment, Continuity, Dynamism, Character Utilization & Consistency, etc.**
- **Structured Prompt Engineering**
- **LLM + RAG Integration & Customization**
- **Domain-Aware Qualitative Analysis**
- **Authored Documents: Series Pitch, Series Bible, Character Bible, Scripts, Pilot, Feedback Structures**
- **Thorough Demonstration of Suitably Complex Real-World Use Case**

---

### 3. [LeafGuard AI: CNN-Based Plant Disease Classification Web Application](https://github.com/JeffreyRobertLynch/leafguard-ai-cv)
LeafGuard is a CNN-based plant disease classifier trained from scratch on the Tomato Leaf Disease Detection dataset. It achieves high accuracy in classifying 10 disease classes, with a full web application that includes batch image processing, confidence score generation, and color-coded visualizations for actionable monitoring. The architecture is designed for scalability, potentially supporting multiple specialized models for facilities with varying needs.

> Full code present in public repo, from notebook training to FastAPI deployment. Models and data required to run the application have been excluded. GUI screenshots and model output images available in the README.

---

**Key Features:**
- **Full AI/ML application:** Frontend and backend integrated with trained models running in hard-coded functions to provide real-time outputs.
- **99.4% accuracy (binary disease detection)**; **94.5% accuracy (multiclassification)** across **10 disease classes**.
- **Batch classification:** Classifies a 24-image batch in under 2 seconds (local), generating confidence scores and batch visualization.
- **Real-world utility:** Color-coded prediction maps for flagging diseased plants by location to enable actionable disease monitoring.
- **Additional features:** Includes model switching, image downloads, and user feedback submission to support future training iterations.
- **User-generated evaluation:** Generate accuracy scores and confusion matrices for any loaded model with optional PNG downloads.

---

**Highlights:**  
- **Production:** Includes well-structured requirements.txt, tested Dockerfile, and README to support collaboration and production deployment.
- **End-to-End Development:** From data to model training to app integration to dockerized deployment.
- **Scalable Architecture:** High-throughput batch processing to handle larger datasets and integration of future models.
- **Custom GUI:** Actionable visual output for easy decision-making and real-time disease monitoring.
- **Full Lifecycle:** From initial academic prototype project to deployed AI/ML web application.

---

### 4. [Customer Scheduling Management System](https://github.com/JeffreyRobertLynch/customer-scheduling-management-system)
- **Full-stack Java application** designed for global business scheduling and reporting.
- Built with MVC and DAO patterns, it features **full CRUD functionality**, and **dynamic report generation**.
- **Automated localization** for all timezones & 15 languages.
- Security features include **password protection** and **user activity auditing**.

---

**Highlights:**  
- **Academic Excellence Award Recipient - Software 2: Advanced Java Concepts:** “Overall, the student's project submission is excellent in that it is an example of quality in work, considering the provided requirements. The backend is informative and organized, while the frontend is easy to use and functional. Excellent job!”
- **Full-Stack Software Engineering**
- **MySQL Database Integration with CRUD (Create, Read, Update, Delete)**
- **Scalable Architecture: MVC + DAO Layers (Model-View-Controller + Data Access Object)**
- **Dynamic Localization: All Time Zones and 15 Languages**
- **Event-Driven GUI Design**
- **Automated Reporting through Prepared Statements**
- **Object Oriented Programming**

---

### 5. [Splunk Integration for Business Intelligence](https://github.com/JeffreyRobertLynch/Splunk-Integration-for-Business-Intelligence)
A comprehensive white paper and executive summary that demonstrates how Splunk can drive data-driven decision-making across Business Analytics, IT Infrastructure, and Cybersecurity Operations. This project earned an Academic Excellence Award for its technical communication, blending technical insight with strategic business awareness.

---

- **Highlights:** 
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
  - Advanced Learning Algorithms Algorithms
- **CompTIA Project+**, **Axelos ITIL v4**, **TEFL**, **Splunk**

---
