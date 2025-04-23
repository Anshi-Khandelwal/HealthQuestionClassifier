# Healthcare Question Classifier + Entity Extractor

This project is a **Healthcare Question Classifier** that classifies healthcare-related questions into categories such as **Symptom**, **Diagnosis**, **Treatment**, **Medication**, and **Urgent**. It also uses **Named Entity Recognition (NER)** to extract important medical entities from the input question, such as symptoms or medications. Additionally, it provides a **Severity Score** to evaluate the urgency of the question.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Running Locally](#running-locally)
- [Deployment](#deployment)
- [License](#license)

---

## Project Overview

The **Healthcare Question Classifier**:
- Classifies healthcare questions into various types (e.g., **Symptom**, **Diagnosis**, **Treatment**).
- Extracts medical entities (such as symptoms and medications) using **Named Entity Recognition (NER)**.
- Calculates a **Severity Score** based on the predicted category (Higher score = more urgent).
- Provides **similar questions** based on the input using **Sentence-Transformers**.

This tool helps in classifying and prioritizing healthcare-related inquiries, making it easier for professionals or automated systems to respond quickly.

---

## Technologies Used

- **Python 3.x**
- **PyTorch** for deep learning and model training.
- **Hugging Face Transformers** for pre-trained models (BERT, DistilBERT).
- **Gradio** for creating the user interface.
- **Sentence-Transformers** for finding similar questions.
- **Scikit-learn** for label encoding.

---

## Installation

### Prerequisites

1. **Python 3.x** (recommended: 3.8 or higher)
2. **pip** for package installation.





