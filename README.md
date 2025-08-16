# <img width="35" height="35" alt="image" src="https://github.com/user-attachments/assets/ea05fa24-092d-49bb-b52a-d7854ccfcbee" /> openai-medical-transcriber 

Extract structured data — including age, medical specialty, and recommended treatment — from anonymized medical transcriptions given in CSV format using the OpenAI API.    
Maps treatments to ICD codes. Built as part of a DataCamp project on real-world NLP in healthcare. 


## 🩺 Project Overview

You have been provided with an anonymized dataset of medical transcriptions organized by specialty (`transcriptions.csv`). The goal is to extract meaningful structured data using natural language processing (NLP) with the OpenAI API.

## 📌 Objectives

- Extract the following fields from each transcription:
  - **Age**
  - **Medical Specialty**
  - **Recommended Treatment**
  
- Match each **recommended treatment** with the corresponding **ICD (International Classification of Diseases)** code.

- Store the structured output in a Pandas DataFrame called `df_structured`.

## 🛠️ Tools & Technologies

- Python 🐍
- Pandas 📊
- JSON 
- OpenAI GPT API 🤖
- ICD Code Mapping 🏷️
- DataCamp Learning Platform

## 📁 Dataset

- `transcriptions.csv`  
  Contains anonymized medical transcriptions grouped by medical specialty.

## ⚙️ How It Works

1. Load and preprocess the transcription data using Pandas.
2. Use the **OpenAI API** to analyze and extract key fields.
3. Map recommended treatments to ICD codes.
4. Store the structured output in `df_structured`.

> ⚠️ *Note:* Since the project uses the OpenAI API, execution time may vary and could take longer due to API response delays.

## 🧪 Output

A structured DataFrame (`df_structured`) with the following columns:
- `age`
- `medical_specialty`
- `recommended_treatment`
- `icd_code`

## 📚 Learning Outcome

- Real-world application of language models in healthcare data
- Automated data structuring from unstructured clinical text
- Integration of GPT with external data systems (ICD codes)

## 📝 Acknowledgments

This project was completed as part of a **DataCamp** learning module on using the OpenAI API for data structuring.

---


