# Resume-Optimizer

🧠 Resume Matcher with OpenAI & Transformers
A simple and interactive Resume Matcher tool that compares a resume and a job description using text embeddings and GPT-based feedback.

# 🚀 Features
Calculates semantic similarity between a resume and a job description using thenlper/gte-base transformer model.

Generates qualitative feedback (strengths, weaknesses, and fit summary) using OpenAI's GPT.

Built with a clean Gradio UI for easy input and output visualization.

# 🛠️ Technologies Used
OpenAI API - For generating natural language feedback.

Hugging Face Transformers - For sentence embeddings using gte-base.

PyTorch - Backend for transformer inference.

Gradio - UI for interactive demo.

Make sure to set your OpenAI API key:

# 💻 How to Use
Open the Open AI Resume Matcher.ipynb file in Colab Notebook
Paste a resume and job description in the respective fields. The tool will:

Compute the cosine similarity between them.

Show a percentage-based match score.

Generate feedback using OpenAI GPT (3 strengths, 3 weaknesses, 1-line summary).

# 📷 Sample Output

🔍 Match Score: 82.5%

# 3 Strengths:
- Strong background in Python.
- Experience in NLP which aligns with the role.
- Prior deployment of ML models.

# 3 Weaknesses:
- Limited mention of scikit-learn specifically.
- No direct mention of pipeline architecture.
- Lacks teamwork or collaboration examples.

# Fit Summary:
Good overall match, but could enhance tool-specific skills in resume.
# 📌 Disclaimer
This is a learning project, not a production tool. I'm still exploring how to work with OpenAI and Hugging Face APIs. Feedback is welcome!
