# Multilingual Government Scheme Recommendation System

**An AI-powered multilingual platform that simplifies access to government welfare schemes through Machine Learning and Natural Language Processing.**

## 1. Project Overview

The Multilingual Government Scheme Recommendation System is designed to improve accessibility to government welfare information by addressing language barriers and information gaps.

The system enables users to explore relevant government schemes, understand eligibility criteria, access benefit details, and learn about application procedures through an intuitive multilingual interface.

It supports **English, Hindi, and Tamil**, making scheme-related information more accessible to a wider range of users.

## 2. Problem Statement

Despite the availability of numerous government welfare schemes, many eligible individuals remain unaware of the benefits and services available to them.

Language barriers, limited digital literacy, and difficulty understanding complex eligibility requirements often prevent people from accessing these schemes.

This project aims to bridge this gap through an intelligent, multilingual recommendation system.

## 3. Key Features

- **Multilingual Interaction:** Supports English, Hindi, and Tamil.
- **Intelligent Scheme Recommendations:** Helps identify relevant government schemes based on user requirements.
- **Eligibility Information:** Simplifies scheme eligibility criteria.
- **Benefits and Coverage:** Provides information about available benefits.
- **Application Assistance:** Explains application procedures and required documents.
- **Voice-Based Interaction:** Integrates speech recognition and text-to-speech capabilities.
- **Personalized Interaction Modes:**
  - Grandma Mode – Simplified explanations for elderly users.
  - Student/Anna Mode – Friendly, conversational responses.
  - Officer Mode – Formal and informative responses.

## 4. Machine Learning Methodology

The system incorporates Natural Language Processing (NLP) and supervised Machine Learning techniques.

**Implementation Workflow**

1. Data Collection
2. Data Preprocessing and Text Cleaning
3. Feature Extraction using TF-IDF Vectorization
4. Machine Learning Model Training
5. Model Evaluation and Comparison
6. Scheme Recommendation and User Interaction

**Models Explored**
- Logistic Regression
- Naive Bayes
- Support Vector Machine (SVM)
- Random Forest

## 5. Government Schemes Covered

The project incorporates information related to the following welfare schemes:

- Ayushman Bharat
- PM-KISAN
- National Scholarship-related scheme information

## 6. Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Machine Learning | Scikit-learn |
| Natural Language Processing | TF-IDF |
| Data Processing | Pandas, NumPy |
| User Interface | Streamlit |
| Voice Processing | Speech Recognition, Text-to-Speech |
| Development Environment | Google Colab |
| Application Tunnelling | ngrok |

## 7. Repository Structure

```text
multilingual-government-scheme-assistant/
│
├── Multilingual_Scheme_Recommendation.ipynb
├── scheme_tfidf.pkl
├── processed_schemes.pkl
└── README.md
```

## 8. Getting Started

**Prerequisites**
- Python
- Google Colab or Jupyter Notebook
- Required Python libraries
- Google Drive access for supporting project files, if applicable

**Setup Instructions**

1. Clone the repository:

```bash
git clone https://github.com/divyasri25032008-cloud/multilingual-government-scheme-assistant.git
```

2. Open the notebook in Google Colab or Jupyter Notebook.

3. Install the required dependencies specified in the notebook.

4. Ensure the supporting model files are accessible.

5. Configure required credentials securely through environment variables or secret management.

6. Execute the notebook cells to initialize the application and explore its functionality.

**Note:** The ngrok authentication token is not included in this repository. Users must configure their own credentials to expose the Streamlit application through ngrok.

## 9. Future Scope

- Expand coverage to additional government welfare schemes.
- Introduce support for more regional languages.
- Improve recommendation performance through model optimization.
- Enhance accessibility for rural communities and users with limited digital literacy.
- Integrate verified and regularly updated government scheme information.

## 10. Author

**Divya Sri K**

GitHub: [divyasri25032008-cloud](https://github.com/divyasri25032008-cloud)

---

*Leveraging Machine Learning and multilingual technology to make government welfare information more accessible and inclusive.*
