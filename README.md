# Automatic Metadata Tagging and Prerequisite Detection in Textual Learning Objects

## Project Overview

This project presents an intelligent framework for automatic metadata generation and prerequisite detection from educational learning resources. The system utilizes Natural Language Processing (NLP) and Machine Learning (ML) techniques to analyze textual content, identify important concepts, classify subjects, and generate structured learning roadmaps.

The primary objective of the project is to transform unstructured educational documents into organized and meaningful learning resources that support effective knowledge acquisition and navigation in e-learning environments.

---

## Objectives

* Automate metadata tagging using NLP and Machine Learning techniques.
* Identify important concepts and keywords from educational documents.
* Detect prerequisite relationships between concepts.
* Generate structured study roadmaps for learners.
* Improve accessibility, searchability, and organization of learning content.

---

## Features

* PDF and TXT document support
* Automatic text extraction
* Text preprocessing and cleaning
* Tokenization, Stopword Removal, and Lemmatization
* TF-IDF based feature extraction
* Subject classification using Multinomial Naive Bayes
* Concept and keyword extraction
* Prerequisite detection
* Study roadmap generation
* Concept relationship visualization
* Interactive Streamlit web interface
* Performance evaluation using Precision, Recall, F1-Score, and Accuracy

---

## Technology Stack

| Component            | Technology              |
| -------------------- | ----------------------- |
| Programming Language | Python                  |
| NLP Library          | NLTK                    |
| Machine Learning     | Scikit-learn            |
| Text Extraction      | PyMuPDF                 |
| Feature Extraction   | TF-IDF                  |
| Classifier           | Multinomial Naive Bayes |
| Interface            | Streamlit               |
| Data Processing      | Pandas, NumPy           |
| Visualization        | NetworkX, Matplotlib    |
| Output Format        | JSON                    |

---

## System Workflow

1. User uploads PDF/TXT learning material.
2. Text is extracted from the document.
3. Text preprocessing is performed:

   * Lowercasing
   * Tokenization
   * Stopword Removal
   * Lemmatization
4. TF-IDF converts text into numerical feature vectors.
5. Multinomial Naive Bayes predicts the document subject.
6. Subject-aware filtering identifies relevant concepts.
7. Keywords and metadata are extracted.
8. Prerequisite relationships are detected.
9. A structured study roadmap is generated.
10. Results are visualized through the Streamlit interface.

---

## Dataset

A custom subject-topic corpus was developed for the project.

### Subject-wise Corpus Distribution

| Subject                                    | Corpus Size |
| ------------------------------------------ | ----------- |
| Programming & Software Development         | 40+         |
| Data Structures                            | 90+         |
| Algorithms                                 | 30+         |
| Computer Networks                          | 40+         |
| Database Systems                           | 120+        |
| Artificial Intelligence / Machine Learning | 100+        |
| Others                                     | 30+         |

The dataset contains more than 400 concepts distributed across multiple Computer Science domains and is stored in CSV format for training and analysis.

---

## Machine Learning Model

The project uses the Multinomial Naive Bayes classifier for subject classification.

### Why Multinomial Naive Bayes?

* Suitable for text classification tasks.
* Works efficiently with TF-IDF features.
* Fast training and prediction.
* Handles high-dimensional textual data effectively.
* Provides strong performance with comparatively low computational cost.

---

## Evaluation Metrics

The system performance is evaluated using:

* Precision
* Recall
* F1-Score
* Accuracy

These metrics help measure the effectiveness of metadata extraction and prerequisite detection.

---

## Project Structure

```text
Automatic-Metadata-Tagging/
│
├── uploads/
├── pdf_tools/
├── subject_model.py
├── train_model.py
├── ui_app.py
├── concept_analysis.py
├── ground_truth.csv
├── requirements.txt
├── README.md
└── model files
```

## Installation

### Clone Repository

```bash
git clone https://github.com/Anjalic0de/Automatic-Metadata-Tagging.git
```

### Move into Project Directory

```bash
cd Automatic-Metadata-Tagging
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run ui_app.py
```

or

```bash
python -m streamlit run ui_app.py
```

---

## Sample Output

The system generates:

* Subject Prediction
* Extracted Concepts
* Metadata Tags
* Concept Relationships
* Prerequisite Dependencies
* Study Roadmap
* Performance Metrics

---

## Future Scope

* Deep Learning based classification models
* Knowledge Graph generation
* Adaptive learning path recommendation
* Multi-language support
* Integration with Learning Management Systems (LMS)
* Real-time educational content analysis

---

## Academic Information

**Project Title:** Automatic Metadata Tagging and Prerequisite Detection in Textual Learning Objects

**Domain:** Natural Language Processing (NLP), Machine Learning, Educational Technology

**Degree:** Bachelor of Technology (B.Tech)

**Branch:** Information Technology

**CGPA:** 7.22/10




---

## Author

**Anjali Verma**

B.Tech Information Technology

---

## License

This project is developed for academic and research purposes.

