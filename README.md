GenAI LinkedIn Post Generator
This tool analyzes the writing style of a LinkedIn influencer and generates new posts that match their tone, topics, and structure.


Imagine Mohan is a LinkedIn influencer. By feeding this tool his past posts, it can:

Analyze and extract key topics and attributes (tone, length, language).

Allow Mohan to select specific configurations.

Generate future posts using few-shot learning to mimic his original style.

🏗️ Technical Architecture

Stage 1: Preprocessing
Scrapes and processes LinkedIn posts, extracting metadata such as topic, tone, and language.

Stage 2: Generation
Uses selected parameters (topic, length, etc.) to generate a new post using few-shot learning and a large language model (LLM).

⚙️ Setup Instructions
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/project-genai-post-generator.git
cd project-genai-post-generator
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Get a Groq API Key:
Visit Groq Console and generate an API key.

Set your environment variable:

bash
Copy
Edit
export GROQ_API_KEY=your_api_key_here
Run the tool:

bash
Copy
Edit
python main.py
📁 File Structure
main.py – Entry point of the application

llm_helper.py – Handles interaction with the language model

few_shot.py – Constructs few-shot examples

post_generator.py – Core generation logic

preprocess.py – LinkedIn post ingestion and cleaning

resources/ – Images for documentation

📌 Requirements
Python 3.7+

OpenAI-compatible Groq API

Packages listed in requirements.txt


