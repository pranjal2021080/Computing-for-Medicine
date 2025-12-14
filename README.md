

---

# 🧬 **Computing for Medicine – Coursework Repository**

---

## 📘 **Repository Overview**

This repository contains **assignments and a comprehensive group project** developed as part of the **Computing for Medicine** course.
The work focuses on applying **computational methods, data standards, and AI techniques** to **real-world healthcare problems**, with a strong emphasis on **interoperability, clinical workflows, and explainability**.

The repository is divided into two major components:

1. **FHIR-based Assignment** – focused on healthcare data modeling and interoperability
2. **AI-powered Medical Project** – focused on intelligent clinical decision support integrated with healthcare standards

---

## 🎯 **Objectives of the Repository**

The primary objectives of this repository are to:

* Apply **FHIR (Fast Healthcare Interoperability Resources)** to real clinical scenarios
* Model healthcare workflows using **standardized medical data formats**
* Demonstrate how **AI systems can integrate with clinical data pipelines**
* Improve **interoperability, automation, and decision support** in healthcare systems
* Maintain **clear academic documentation and reproducible artifacts**

---

## 📂 **Repository Structure**

```
Computing-for-Medicine
│
├── Assignment_1_FHIR_Storyboarding
│   ├── Assignment_1_FHIR_Storyboarding.pdf
│   ├── FHIR_Resources
│   │   └── bundle.json
│   └── Diagrams
│       ├── UML_Diagram.pdf
│       └── User_Workflow_Diagram.pdf
│
└── Project_AI_Radiology_Assistant
    ├── Project_Report.pdf
    ├── Presentation
    │   └── CM_GROUP_8.pptx
    ├── FHIR_Artifacts
    │   └── DiagnosticReport_Bundle.json
    ├── Diagrams
    │   └── System_Architecture.pdf
    └── Demo
        └── Demo_Video.mp4
```

Each folder is **self-contained**, clearly labeled, and aligned with coursework requirements.

---

## 🧾 **Assignment 1 – FHIR Storyboarding**

### 📌 **Problem Addressed**

The assignment models a **remote blood pressure monitoring system** for patients with chronic hypertension.
The goal is to demonstrate how **FHIR resources can be used to exchange healthcare data seamlessly** between wearable devices, monitoring systems, clinicians, and electronic health records (EHRs).

---

### 🏥 **Clinical Use Case**

* A patient wears a **smartwatch** that records blood pressure readings
* Readings are transmitted to a **remote monitoring system**
* If blood pressure exceeds safe thresholds:

  * The system alerts the **physician**
  * The physician updates the **care plan and medication**
* The system supports **continuous monitoring, early intervention, and proactive care**

---

### 🧩 **FHIR Resources Used**

The assignment models the workflow using standardized FHIR resources, including:

* **Patient** – Represents the individual receiving care
* **Device** – Represents the wearable BP monitor
* **Observation** – Stores blood pressure readings
* **RiskAssessment** – Estimates risk of hypertensive crisis
* **Communication** – Sends alerts to clinicians
* **CarePlan** – Manages treatment strategy
* **MedicationRequest** – Records prescribed medication
* **Practitioner** – Represents the treating physician
* **Goal** – Defines target blood pressure values

All resources are combined into a **FHIR Bundle** represented in **FHIR-compliant JSON**.

---

### 📊 **Artifacts Included**

* Storyboard document (PDF)
* FHIR Bundle (`bundle.json`)
* UML diagram showing resource relationships
* User workflow diagram illustrating data flow

---

### ✅ **Outcome**

This assignment demonstrates how FHIR:

* Enables **interoperable healthcare data exchange**
* Reduces fragmentation across systems
* Improves clinical workflow efficiency
* Supports continuous and preventive care models

---

## 🧪 **Project – AI-Powered Radiology Assistant**

### 📌 **Project Motivation**

Radiological image interpretation is time-consuming and requires expert analysis.
In many healthcare settings, especially low-resource environments, there is a shortage of radiologists.

This project explores how **AI, NLP, and FHIR interoperability** can be combined to:

* Assist in **preliminary radiological diagnosis**
* Generate **structured, explainable clinical reports**
* Integrate seamlessly with healthcare information systems

---

### 🤖 **Core Components**

The project integrates multiple layers:

1. **Fine-Tuned CLIP Model**

   * CLIP is adapted to the medical domain using a radiology-specific dataset
   * Enables image-to-text retrieval and diagnosis generation

2. **Context-Aware Medical Chatbot**

   * Responds to user queries using diagnostic output
   * Provides safe, non-prescriptive clinical guidance
   * Always includes clinician-consultation disclaimers

3. **Explainability Layer**

   * Generates **attention heatmaps** to highlight diagnostic regions
   * Improves trust and interpretability of AI decisions

4. **FHIR Interoperability Layer**

   * Converts AI findings into structured **FHIR DiagnosticReport**
   * Maps clinical concepts to **SNOMED CT** and **LOINC**
   * Ensures compatibility with EHR systems

---

### 📄 **Project Artifacts**

* Detailed project report
* Presentation slides
* FHIR DiagnosticReport bundle (JSON)
* Architecture and workflow diagrams
* Demo video showing system functionality

---

## 🛠️ **Technologies & Standards Used**

* Python
* Multimodal AI (CLIP)
* Natural Language Processing
* FHIR (HL7)
* SNOMED CT & LOINC
* JSON-based healthcare data exchange
* UML & workflow modeling

---

## 🎓 **Learning Outcomes**

This repository demonstrates:

* Practical use of **FHIR for healthcare interoperability**
* Integration of **AI systems into clinical workflows**
* Importance of **standardized medical data**
* Ethical, safe, and explainable AI design
* Professional academic documentation and structuring

---

## 📌 **Intended Audience**

This repository is useful for:

* Students studying **health informatics or medical AI**
* Researchers exploring **FHIR-based systems**
* Educators evaluating coursework
* Developers interested in **AI + healthcare integration**

---


Just tell me 👍
