## 📄 Dataset: `transcriptions.csv`

This dataset contains **anonymized medical transcription records** categorized by medical specialty. Each row includes a detailed, free-text clinical note and the corresponding medical specialty.

### 📋 Structure

| Column             | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| `medical_specialty` | The medical domain or department (e.g., Allergy / Immunology, Orthopedic). |
| `transcription`     | A full clinical note with sections like SUBJECTIVE, OBJECTIVE, PLAN, etc.  |

The transcriptions may include:
- **Patient demographics** (e.g., age, gender)
- **Medical history**
- **Symptoms and observations**
- **Medications and allergies**
- **Diagnosis and treatment plans**

### 🧪 Sample Rows

| medical_specialty     | transcription (excerpt) |
|-----------------------|--------------------------|
| Allergy / Immunology  | *"This 23-year-old female presents with complaints of allergies..."* |
| Orthopedic            | *"Mr. XYZ, 41, ruptured his Achilles tendon while playing basketball..."* |

### 🛠 Use Case

The dataset is ideal for:
- Natural Language Processing (NLP)
- Clinical information extraction
- Medical coding and ICD mapping
- AI-driven health record structuring
