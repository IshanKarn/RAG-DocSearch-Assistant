# RAG-DocSearch-Assistant

## Introduction
**RAG-DocSearch-Assistant** is a Retrieval-Augmented Generation (RAG) based AI assistant designed to help startups prepare structured meeting plans. It leverages investor pitch decks, terms and conditions documents, and previous meeting notes or presentations to retrieve relevant context and generate clear, actionable meeting agendas and strategies.

## Features
* **Document Ingestion**: Seamlessly processes investor pitch decks, legal terms, and meeting notes.
* **Contextual Retrieval**: Uses RAG to extract precise insights across complex documents.
* **Automated Agenda Generation**: Constructs structured meeting plans tailored to your goal.
* **Interactive Web Interface**: Streamlined user experience powered by Streamlit.

---

## Directory Structure
```text
RAG-DocSearch-Assistant/
├── .devcontainer/         # Dev container configuration files
├── .gitignore             # Files and directories ignored by Git
├── app.py                 # Main application script (Streamlit / UI entry point)
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation
```

---

## Setup

### Prerequisites
* **Python**: 3.9 or higher
* **Git**: Installed on your local machine

### Clone the Repository
```bash
git clone [https://github.com/IshanKarn/RAG-DocSearch-Assistant.git](https://github.com/IshanKarn/RAG-DocSearch-Assistant.git)
cd RAG-DocSearch-Assistant
```

---

### Virtual environemnt

### On macOS / Linux
python3 -m venv venv
source venv/bin/activate

### On Windows
python -m venv venv
venv\Scripts\activate

---

### Installation

Install all required Python packages using `requirements.txt`:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```
---

## Run

To launch the assistant application:

```bash
streamlit run app.py
```
