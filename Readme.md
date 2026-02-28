# 🏗 Civil Engineering Insight Studio

## 📌 Overview

Civil Engineering Insight Studio is a cloud-based AI-powered web application designed to analyze images of civil engineering structures and generate structured technical descriptions.

The system leverages a transformer-based Vision-Language Model to automatically interpret structural images and convert them into organized engineering data fields.

This solution reduces manual documentation effort, improves reporting consistency, and accelerates structural assessment workflows.

## 🚧 Problem Statement

Civil engineers frequently document structural elements manually from images. This process is:

- Time-consuming
- Subjective
- Inconsistent across teams

There is a need for an automated system capable of analyzing structural images and generating:

- Structure Type
- Materials Used
- Structural Components
- Construction Methods
- Notable Features
- Visible Defects

This project provides a cloud-based solution for automated structural image analysis.

## ✨ Key Features

- Image upload for civil engineering structures
- AI-based automatic caption generation
- Domain-specific engineering parsing
- Structured JSON output
- Downloadable structural analysis report
- Web-based user interface built with Streamlit

## 🛠 Technologies Used

- Python
- Streamlit
- Transformers (Hugging Face)
- BLIP Vision-Language Model
- PyTorch
- Pillow

## 🏗 System Architecture

### Workflow
```text
        ┌─────────────┐
        │    User     │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │     Web     │
        │  Interface  │
        │ (Streamlit) │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │   Vision-   │
        │  Language   │
        │ Model (BLIP)│
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │ Engineering │
        │   Domain    │
        │   Parser    │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │ Structured  │
        │    JSON     │
        │   Output    │
        └──────┬──────┘
               ↓
        ┌─────────────┐
        │ Downloadable│
        │    Report   │
        └─────────────┘
```

## ⚙ Installation Instructions

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/CivilEngineeringInsightStudio.git
```

### 2️⃣ Navigate to Project Directory
```bash
cd CivilEngineeringInsightStudio
```

### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 4️⃣ Run the Application
```bash
streamlit run app.py
```

### 5️⃣ Open in Browser
```bash
http://localhost:8501
```

## 📊 Sample Output Structure

The system generates structured output including:

- Structure Type
- Materials Detected
- Structural Components
- Construction Methods
- Estimated Dimensions
- Notable Features
- Visible Defects
- Confidence Score

## ⚠ Limitations

- Dimension estimation is approximate
- Accuracy depends on image quality
- Model provides visual estimation only (no physical structural testing)

## 🚀 Future Enhancements

- Integration with advanced structural defect detection models
- 3D structural analysis capability
- Database integration for project tracking
- Deployment on scalable cloud infrastructure

## 👥 Project Team

- **YECHURI V R NARAYANA KARTHIKEYA 

### Institution 
ADITYA COLLEGE OF ENGINEERING AND TECHNOLOGY 

Year: 2026
