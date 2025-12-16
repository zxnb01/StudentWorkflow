# Student Workflow – Lecture to Study Materials

A fully automated system that converts a recorded lecture into structured study materials using AI.

Once a lecture file is provided, the entire pipeline runs automatically — from transcription to notes, flashcards, and PDF generation — without any manual intervention.

---

## 🎯 Objective
Help students turn long recorded lectures into concise, exam-ready study resources.

---

## 🔄 Automated Pipeline

Lecture File  
→ Audio Extraction  
→ Speech-to-Text Transcription  
→ AI-based Content Processing  
→ Study Notes & Flashcards  
→ Downloadable Outputs (PDF / Text)

---

## 🛠 Technologies Used

- **Python**
- **Google Colab**
- **FFmpeg** – audio extraction
- **Faster-Whisper** – speech-to-text transcription
- **Google Gemini API** – generating notes and flashcards
- **ReportLab** – PDF generation
- **Git & GitHub**

---

## 📂 Project Structure

```bash
StudentWorkflow/
├── Student_Workflow.ipynb
├── README.md
├── prompts/
│ ├── notes.txt
│ └── flashcards.txt
├── samples/
│ └── sample_lecture.mp4
└── outputs/
├── transcript.txt
├── notes.md
├── flashcards.txt
└── study_material.pdf
```
---

## ▶️ How to Run

1. Open `Student_Workflow.ipynb` in **Google Colab**
2. Upload a lecture file (`.mp4`, `.mp3`, `.wav`)
3. Run all cells top to bottom
4. Download generated materials from the `outputs/` folder
   
---

## 📌 Sample Output

Generated files:
- `notes.md`
- `flashcards.txt`
- `study_material.pdf`

See the `outputs/` folder for examples.
