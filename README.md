# 🧠 InsightMate: Local Feedback Analytics with LLaMA 2

**Developed by Aishwarya Chand**  
A lightweight, privacy-first feedback analytics engine powered by LLaMA 2 via Ollama, designed to help product teams extract **key themes, sentiment**, and **feature requests** from raw user feedback.

---

## 🚀 Key Features

- 🔒 **Local-first**: Runs entirely offline using Ollama for LLaMA 2 model inference
- ✨ **Summarization**: Converts long-form feedback into concise summaries
- 💡 **Theme Extraction**: Identifies recurring pain points and product suggestions
- 🎯 **Sentiment Analysis**: Tags feedback with positive, neutral, or negative sentiment
- 📊 **Decision Support**: Outputs structured data to guide product roadmap

---

## 🛠️ Tech Stack

- Python, Ollama, LLaMA 2
- Pandas, Regex, Prompt Engineering
- Modular architecture for easy scaling

---

## 📂 Project Structure

- `app/`: Core logic including prompt templates and LLM interfacing
- `data/`: Sample feedback data
- `outputs/`: Example generated summaries
- `tests/`: Unit tests for key components

---

## 🧪 How to Run

```bash
# Step 1: Install Ollama and Python packages
brew install ollama  # Mac
ollama run llama2

# Step 2: Clone and install
git clone https://github.com/yourusername/InsightMate.git
cd InsightMate
pip install -r requirements.txt

# Step 3: Run the summarizer
python app/main.py --input data/sample_feedback.csv --output outputs/summary.json
