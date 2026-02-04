# CURA-Autism AI

CURA-Autism AI is an advanced, AI-enabled platform designed to support the entire autism care lifecycle, from early screening and diagnostic support to long-term care management. The platform empowers healthcare professionals, caregivers, and educators with AI-driven insights while ensuring human-in-the-loop decision-making and ethical AI practices.

## 🚀 Core Modules

### 1. AI-Enabled Early Screening
Supports primary caregivers and educators in identifying potential autism indicators through age-adaptive questionnaires and AI-driven risk scoring with clear explanations.

### 2. Clinical Decision Support
Assists clinical professionals by structuring and summarizing patient notes, cross-referencing symptoms against established diagnostic criteria, and retrieving relevant guidelines via a RAG system.

### 3. Post-Diagnosis Care Management
Facilitates the creation and tracking of personalized care plans, suggesting evidence-based interventions and providing age-appropriate educational resources for families.

## 🛡️ Key Principles

- **Responsibile & Explainable AI**: Every AI insight is accompanied by confident levels and transparent reasoning.
- **Privacy & Security**: Built with privacy-by-design, utilizing synthetic data for training and implementing robust encryption (AES-256/TLS 1.3).
- **Accessibility**: Committed to WCAG 2.1 AA standards to ensure usability for all.
- **Interoperability**: Supports standard healthcare data formats (HL7 FHIR) for seamless EHR integration.

## 🏗️ System Architecture

The platform uses a modular microservices architecture:
- **Presentation Layer**: Multi-platform web and mobile apps.
- **Application Layer**: Specialized services for Screening, Clinical Support, Care Management, and AI capabilities.
- **Data Layer**: Secure storage using PostgreSQL, Vector Databases (for RAG), and Redis caching.

## 📂 Documentation

Detailed documentation is available in the repository:
- [Requirements Specification](requirements.md)
- [Design Document](design.md)

---
*Disclaimer: CURA-Autism AI is designed as a support tool for healthcare professionals and is not a replacement for clinical diagnosis or medical judgment.*
