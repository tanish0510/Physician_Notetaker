# 🏥 Medical NLP Pipeline  

## 📌 Project Overview  
This project implements a **Medical NLP Pipeline** for processing **physician-patient conversations**, extracting medical insights, analyzing sentiment & intent, and generating **SOAP notes**. The system combines **spaCy, Transformers (BERT), and rule-based methods** for structured text processing.  

---

## 🚀 Features  
✔ **Conversation Parsing** → Extracts physician & patient dialogues.  
✔ **Named Entity Recognition (NER)** → Identifies **symptoms, treatments, diagnoses, prognoses** using spaCy.  
✔ **Sentiment & Intent Analysis** → Classifies **emotions (Anxious, Neutral, Reassured)** and detects **patient intent**.  
✔ **SOAP Note Generation** → Converts extracted information into **structured medical reports**.  
✔ **Medical Data Visualization** → Creates **word clouds, network graphs, patient timelines, and sentiment charts**.  
✔ **Handling Missing Data** → Ensures **structured summaries** even with incomplete inputs.  
---
## ⚙️ Installation & Setup  
### **1️⃣ Clone the Repository**  
```bash
  git clone https://github.com/tanish0510/Physician_Notetaker
  cd Medical-NLP-Pipeline
```

### **2️⃣ Create Virtual Environment & Install Dependencies**
```bash
python -m venv env  
source env/bin/activate  # For macOS/Linux  
env\Scripts\activate  # For Windows  
pip install -r requirements.txt
```

### **3️⃣ Download spaCy Model**
```bash
python -m spacy download en_core_web_lg
```
## 🛠️ Methodologies Used

### 🔹 Named Entity Recognition (NER)
	•	spaCy (en_core_web_lg) for entity detection.
	•	Rule-based keyword extraction for symptoms, treatments, and diagnoses.

### 🔹 Sentiment & Intent Analysis
	•	DistilBERT-based Transformer model for sentiment classification.
	•	Rule-based heuristics for intent classification.

### 🔹 SOAP Note Generation
	•	Automatically structures medical reports into Subjective, Objective, Assessment, and Plan (SOAP) format.

### 🔹 Data Visualization
	•	Word Clouds → Highlights common medical terms.
	•	Network Graphs → Shows relationships between symptoms, diagnoses, and treatments.
	•	Sentiment Charts → Tracks patient emotion progression.
📊 Sample Output Screenshots

## 🔹 Sentiment Analysis Results
### Patient Sentiment
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.06.52%E2%80%AFAM.png)

### Patient Intent Distribution
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.06.57%E2%80%AFAM.png])

### WordCloud
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.07.49%E2%80%AFAM.png)

### Network Graph
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.08.01%E2%80%AFAM.png)

### Patient Journey Timeline
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.08.10%E2%80%AFAM.png)

### Patient Sentiment Progression
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.08.29%E2%80%AFAM.png)

### SOAP Note Visualization
![RESULTS](https://github.com/tanish0510/Physician_Notetaker/blob/main/snaps/Screenshot%202025-03-11%20at%2012.08.21%E2%80%AFAM.png)
