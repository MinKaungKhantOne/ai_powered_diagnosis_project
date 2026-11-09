# AI-Powered Symptoms and Disease Diagnosis System

## Project Overview

The AI-Powered Symptoms and Disease Diagnosis System is a web-based healthcare application developed using Python and Django. It uses a Machine Learning model based on the Random Forest algorithm to predict possible diseases based on symptoms reported by patients.

In addition to disease prediction, the application provides a healthcare knowledge-sharing section where users can read health-related articles to improve their understanding of different diseases, symptoms, and healthcare topics.

The main goal of this project is to combine Machine Learning and healthcare information sharing in one platform.

## Key Features

### 1. AI-Powered Disease Prediction
- Allows users to select or provide their symptoms.
- Uses a trained Random Forest Machine Learning model to analyze the selected symptoms.
- Predicts possible disease names based on symptom patterns.
- Provides prediction results through a web interface.

### 2. Healthcare Knowledge Sharing
- Provides a dedicated article-reading page.
- Allows users to read healthcare-related articles.
- Helps users improve their knowledge of diseases, symptoms, and general healthcare information.

### 3. Machine Learning Model Development
- Collected and prepared symptom-related datasets.
- Performed data preprocessing to make the dataset suitable for model training.
- Developed and trained a Random Forest classification model.
- Validated the trained model to evaluate its predictive performance.

## Technologies Used

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Backend Framework | Django |
| Machine Learning | Scikit-learn |
| ML Algorithm | Random Forest |
| Frontend | HTML, CSS, Tailwind CSS |
| Data Processing | Pandas, NumPy |

## My Contributions

- Collected and organized symptom-related datasets for disease prediction.
- Performed data preprocessing to prepare structured data for Machine Learning.
- Developed and trained a Random Forest classification model.
- Validated the Machine Learning model to evaluate its performance.
- Integrated the trained model into the Django application for disease prediction.
- Developed application functionality for symptom-based disease prediction.
- Implemented a healthcare article-reading page to support knowledge sharing.

## Project Structure

The project is developed using the Django framework, with separate components for web application functionality and Machine Learning.

## Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/MinKaungKhantOne/ai_powered_diagnosis_project.git
```

### 2. Navigate to the Project Directory

```bash
cd ai_powered_diagnosis_project
```

### 3. Create a Virtual Environment

```bash
python -m venv venv
```

### 4. Activate the Virtual Environment

**Windows:**
```bash
venv\Scripts\activate
```

**macOS / Linux:**
```bash
source venv/bin/activate
```

### 5. Install Dependencies

```bash
pip install -r requirements.txt
```

### 6. Run Database Migrations

```bash
python manage.py migrate
```

### 7. Start the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

```text
http://127.0.0.1:8000/
```

## Machine Learning Workflow

The disease prediction model follows these main steps:

1. **Data Collection:** Collect symptom-related data and disease labels.
2. **Data Preprocessing:** Clean and prepare the dataset for Machine Learning.
3. **Model Training:** Train a Random Forest classification model using the prepared dataset.
4. **Model Validation:** Evaluate the trained model using validation data.
5. **Model Integration:** Integrate the trained model into the Django web application.
6. **Prediction:** Analyze patient-reported symptoms and predict possible diseases.

## Disclaimer

This application is an academic project developed for educational and learning purposes. Its disease predictions are not a substitute for professional medical diagnosis, advice, or treatment. Users should consult qualified healthcare professionals for medical concerns.

## Author

**Min Kaung Khant**

- GitHub: [MinKaungKhantOne](https://github.com/MinKaungKhantOne)

