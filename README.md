
# 🧠 GenAI LinkedIn Post Generator

This project analyzes a LinkedIn influencer's past posts and generates new content that mimics their unique writing style using few-shot learning and LLMs.

![Tool UI](resources/tool.jpg)

---

## 🚀 Features

- Extracts writing style, tone, and structure from previous LinkedIn posts.
- Lets users choose topic, length, and language for new posts.
- Uses few-shot learning with a large language model for natural post generation.

---

## 🧰 Tech Stack

- **Python**
- **LLMs (via Groq API)**
- **Few-shot learning**
- **Data preprocessing with custom scripts**

---

## 🏗️ Architecture

![Architecture](resources/architecture.jpg)

1. **Preprocessing**: Collect and clean LinkedIn posts.
2. **Generation**: Feed selected attributes + few-shot examples to LLM.
3. **Post Output**: Return style-matching LinkedIn post.

---

## ⚙️ Setup

### 1. Clone this repo

```bash
git clone https://github.com/your-username/project-genai-post-generator.git
cd project-genai-post-generator
```

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Get API Key

- Create a free account at [Groq Console](https://console.groq.com/keys)
- Export your API key:
```bash
export GROQ_API_KEY="your_key_here"
```

### 4. Run the tool

```bash
python main.py
```

---

## 📁 Folder Structure

```bash
├── few_shot.py         # Few-shot learning logic
├── llm_helper.py       # API interaction with LLM
├── main.py             # Script entry point
├── post_generator.py   # Core logic to generate posts
├── preprocess.py       # Data collection and preprocessing
├── requirements.txt
├── README.md
└── resources/
```

---

## ✅ Requirements

- Python >= 3.7
- API Key from Groq
- Dependencies from `requirements.txt`

---




