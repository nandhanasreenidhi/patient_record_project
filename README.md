# 🩺 Blood Work Analyzer

An AI-powered Streamlit application that analyzes blood work reports and generates a simple health summary along with a practical Indian diet plan.

The application uses **LangChain + Google Generative AI** to process the provided blood report and present the results in an easy-to-understand format.

## 🚀 Live Demo

**[Open Blood Work Analyzer](https://patientrecordproject-iyuer565rq8owneyntfjtn.streamlit.app/)**

## ✨ Features

* 📄 Paste blood work reports directly into the application
* 🔍 Extract and classify test values as **HIGH, LOW, or NORMAL**
* 🧠 Generate a simplified health summary using an LLM
* 🥗 Generate a practical Indian diet plan
* 🖥️ Clean two-column Streamlit interface
* ⚡ Real-time AI-powered analysis

## 🛠️ Tech Stack

* **Python**
* **Streamlit** — web application interface
* **LangChain** — LLM integration
* **Google Generative AI** — AI-powered analysis
* **python-dotenv** — environment variable management

## 🔄 How It Works

```text
User enters blood work report
            ↓
      Streamlit Interface
            ↓
     LangChain Integration
            ↓
    Google Generative AI
            ↓
  Extract & classify test values
            ↓
     Health summary + 
     Indian diet suggestions
```

## 📁 Project Structure

```text
patient_record_project/
│
├── streamlit/
│   └── app.py
│
├── bloodwork.txt
├── health_analysis.ipynb
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/nandhanasreenidhi/patient_record_project.git
cd patient_record_project
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Configure the Google API key

Create a `.env` file in the project root:

```text
GOOGLE_API_KEY=your_api_key_here
```

**Do not commit the `.env` file to GitHub.**

### 4. Run the application

```bash
streamlit run streamlit/app.py
```

The application will open locally at:

```text
http://localhost:8501
```

## 🔐 Deployment

The application is deployed using **Streamlit Community Cloud**.

The Google API key is configured through Streamlit's secrets management rather than being stored in the source code.

## ⚠️ Disclaimer

This project is intended as an **educational/demo application** for exploring AI-assisted health-data analysis. The generated information is not a medical diagnosis and should not replace advice from a qualified healthcare professional.

## 👩‍💻 Author

**Nandhana Sreenidhi**

B.Tech — Artificial Intelligence & Data Science
