🩺 Clinical Note Simplifier — AI for Patient-Friendly Discharge Summaries
Transforming complex clinical notes into clear, compassionate language — using fine-tuned Large Language Models.

🔍 Overview
Clinical notes are critical for doctors, but often unreadable to patients. This project uses a fine-tuned T5-base model (with LoRA + PEFT) to simplify medical shorthand and jargon into easy-to-understand summaries.

Example:
Input: Pt admitted w/ DKA. Treated w/ prednisone, statin. D/C stable.
Output: You were admitted for a diabetes complication. You were treated with prednisone and statin. You're now stable. Please follow up soon.

🚀 Demo
👉 Try the app on Hugging Face Spaces

🛠️ What’s Under the Hood
Model: T5-base, fine-tuned with LoRA & PEFT using Hugging Face Transformers

Dataset: 1,500+ augmented, real-world clinical examples

Preprocessing: Abbreviation expansion + tone-aware prompts

Deployment: Gradio UI on Hugging Face Spaces

🧠 Key Features
Converts dense medical text into readable summaries

Expands common clinical abbreviations (e.g., "SOB" → "shortness of breath")

Provides friendly, reassuring tone for patient understanding

Supports real-time inference via Hugging Face

📦 How to Run Locally
bash
Copy
Edit
git clone https://github.com/your-username/clinical-note-simplifier.git
cd clinical-note-simplifier

# Create and activate environment
pip install -r requirements.txt

# Run the app
python app.py
Make sure your merged_t5_clinical folder with the fine-tuned model is in the root directory.

🧰 Tech Stack
Python, PyTorch

Hugging Face Transformers, PEFT

Gradio for UI

T5-base with Low-Rank Adaptation (LoRA)

Streamlit (optional version)

🎯 Goal
To empower patients by translating medical complexity into human clarity — improving trust, education, and health outcomes.

📍 About the Author
👋 I’m Harisudhan Veerasamy, a DevOps Engineer with a growing passion for MLOps and LLM deployment. Based in Galway, Ireland 🇮🇪 — building real-world AI tools that solve real problems.

Connect with me: LinkedIn
