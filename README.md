# 🧠 ResearchMind OS

> Autonomous Multi-Agent AI Research Platform powered by GPT-4o-mini, LangChain, Tavily Search, and Streamlit.

ResearchMind OS is an end-to-end AI research system that autonomously searches the web, extracts relevant information, synthesizes findings into a structured report, and critiques its own output using a team of specialized AI agents.

---

## 🚀 Features

### 🔍 Search Agent

* Searches the web for recent and reliable information
* Uses Tavily Search API
* Collects high-quality sources and summaries

### 📄 Reader Agent

* Scrapes and extracts content from relevant sources
* Cleans webpages and removes unnecessary elements
* Produces focused research material

### ✍️ Writer Agent

* Generates detailed research reports
* Structures information into:

  * Introduction
  * Key Findings
  * Conclusion
  * References

### 🧐 Critic Agent

* Evaluates generated reports
* Provides strengths and weaknesses
* Assigns an overall quality score

### 🎨 Modern Streamlit Interface

* Interactive research workflow
* Multi-agent pipeline visualization
* Downloadable research reports
* Dark-themed research dashboard

---

## 🏗️ System Architecture

```text
User Query
     │
     ▼
┌─────────────┐
│ Search Agent│
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Reader Agent│
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Writer Agent│
└──────┬──────┘
       │
       ▼
┌─────────────┐
│ Critic Agent│
└──────┬──────┘
       │
       ▼
 Research Report
```

---

## 🛠️ Tech Stack

### AI & LLMs

* GPT-4o-mini
* LangChain

### Research & Retrieval

* Tavily Search API
* Requests
* BeautifulSoup

### Frontend

* Streamlit

### Utilities

* Python
* dotenv

---

## 📂 Project Structure

```bash
.
├── app.py
├── agents.py
├── pipeline.py
├── tools.py
├── requirements.txt
├── .env
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/researchmind-os.git
cd researchmind-os
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

Windows

```bash
venv\Scripts\activate
```

Linux / Mac

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root.

```env
OPENAI_API_KEY=your_openai_key

TAVILY_API_KEY=your_tavily_key
```

---

## ▶️ Run Streamlit App

```bash
streamlit run app.py
```

Open:

```text
http://localhost:8501
```

---

## 📸 Demo Workflow

1. Enter a research topic
2. Search Agent gathers information
3. Reader Agent extracts detailed content
4. Writer Agent generates a structured report
5. Critic Agent evaluates the report
6. Download the final research document

---

## 🎯 Example Topics

* AI Agents in 2026
* Quantum Computing Breakthroughs
* Fusion Energy Progress
* CRISPR Gene Editing
* Future of Autonomous Vehicles

---

## 🔮 Future Improvements

* Multi-source scraping
* Citation tracking
* PDF export
* Research depth modes
* Source ranking
* Agent memory
* LangGraph workflow orchestration
* Streaming report generation

---

## 👨‍💻 Author

Arpit Kumar

Computer Science Engineering (Data Science)

Interested in:

* Artificial Intelligence
* Machine Learning
* Data Science
* Autonomous AI Systems

---

## ⭐ If you found this project useful, consider starring the repository.
