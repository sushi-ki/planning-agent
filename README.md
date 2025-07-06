## 🧠 Planning Agent for Deep Research & Structured Report Generation

This project showcases a powerful Planning Agent built using LangGraph and integrated tools to automate the entire process of deep research and wiki-style structured report generation on any topic.

### 📌 Overview

The Planning Agent is designed to:

Accept a topic of interest from the user.
Automatically plan the structure of a detailed report.
Conduct deep web research in parallel using tools like Tavily Search.
Write coherent and structured content for each section.
Generate a high-quality, ready-to-use report including an introduction, key sections, and conclusion.
⚠️ Note: This project can generate a high number of web queries and may exceed your API limits for Tavily Search on the free tier.

## 🛠 Features

✅ Automated Report Planning: Based on the topic, the agent determines an optimal structure for the report.
🔍 Web-Integrated Research: Uses real-time data from the web to ensure fresh, relevant information.
⚙️ Parallel Processing: Executes research and section writing in parallel to boost efficiency.
📝 Structured Content Generation: Divides report into introduction, main sections, and conclusion.
📚 Final Compilation: Merges all generated content into a polished final report.

## 🧩 Tech Stack

LangGraph – for building composable and stateful agents.
LangChain – for prompt orchestration and tool chaining.
Tavily API – for live web search data.
Python – primary programming language.
Jupyter Notebook – for experimentation and execution.

## 🚀 How It Works

Topic Input: You provide a research topic.
Planning Stage:
The agent defines key report sections.
Determines relevant subtopics.
Parallel Agent Actions:
Researcher Node: Fetches real-time data via Tavily.
Writer Node: Drafts content using retrieved context.
Structuring:
Formats the sections for consistency.
Writes the introduction and conclusion.
Output:
All content is compiled into a final, human-readable report.

## 📦 Installation

Clone the repository:
git clone https://github.com/sushi-ki/planning-agent
cd planning-agent
Create and activate a virtual environment:
python -m venv venv
source venv/bin/activate  # on Windows use `venv\Scripts\activate`
Install dependencies:
pip install -r requirements.txt

## 🧪 Example Output

For a topic like "Quantum Computing in Cybersecurity", the agent may generate a report with the following sections:

Introduction
The Basics of Quantum Computing
Quantum Threats to Modern Encryption
Post-Quantum Cryptography
Conclusion
Each section is researched and written using real-time web data, formatted into a clean wiki-style structure.

## 📁 Files

planning agent for deep research and structured report.ipynb: Main Jupyter notebook with all implementation steps.
README.md: Project overview.
requirements.txt: Required Python libraries (you can generate this by running pip freeze > requirements.txt in your virtual environment).

## 💡 Use Cases

Research assistants and students writing reports.
Knowledge base automation.
Wikis and technical documentation.
Journalism and content creation automation.


## 🧠 Inspiration

This project was inspired by LangGraph’s capability to chain LLM tools for structured reasoning and long-term planning. It blends the power of prompt engineering, parallel execution, and real-time search into one automated pipeline.

## 📬 Contact

For feedback, improvements, or collaboration:
Kirti Khatri
📧 https://www.linkedin.com/in/kirti-khatri-683426327/
🌐 github.com/sushi-ki
