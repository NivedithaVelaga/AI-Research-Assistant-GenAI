# AI-Research-Assistant-GenAI

A lightweight AI-powered research assistant that fetches **real-time news and updates** about any given subject using **Tavily Search API** and **Google Gemini 1.5 Pro**.

This assistant takes just a few words (e.g., "Scramjet Engine") as input and returns the latest developments, research updates, and a curated summary — all in clean human-like language.

---

##  Features
-   Real-time search and data fetching using Tavily API
-   Human-like summarization with Google Gemini 1.5 Pro
-   Tool-calling architecture between LLM and external search tools
-   Displays source websites for transparency
-   Robust error handling for network issues

---

##  Tools & Technologies Used
- **Python 3.13**
- **Google Gemini 1.5 Pro (via google-generativeai)**
- **Tavily Search API**
- **Requests Library**
- **JSON Parsing**
- **Prompt Engineering for LLMs**

---

##  How to Run the Project Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
   cd YOUR-REPO-NAME
2. Install the required libraries
   - pip install -r requirements.txt

4. Setup your API keys
   - Get your Tavily API Key from https://tavily.com/
   - Get your Gemini API Key from Google AI Studio
     
5. Run the application
   - python main.py
     
 Example Usage
Input:

Subject: "Scramjet Engine"

Output:

Here are some recent updates:

- India successfully tested Scramjet engine for 1000 seconds.

- NASA announced new developments in scramjet-based space travel.

Sources:

- NASA.gov

- ISRO.in

 Important Notes
- This project is for educational and learning purposes.

- Always cross-verify live data sources.

- LLM outputs might occasionally be hallucinated, verify critical information manually.

Author: Niveditha Velaga
GitHub: NivedithaVelaga
