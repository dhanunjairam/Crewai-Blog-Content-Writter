# 🧠 AI Content Generator using CrewAI and Streamlit

This is a Streamlit-based web application that uses [CrewAI](https://github.com/joaomdmoura/crewAI) and LLaMA 3.3 via OpenRouter to generate structured, SEO-friendly blog content from a single topic input. It simulates a collaborative writing workflow involving three AI agents:

- **Planner**: Researches the topic and outlines the blog.
- **Writer**: Writes the full blog based on the plan.
- **Editor**: Proofreads and polishes the content.

---

## 🚀 Features

- ✅ Simple UI to input your blog topic
- ✅ Generates high-quality blog posts in markdown format
- ✅ Uses agents for planning, writing, and editing
- ✅ Built with OpenRouter’s Meta LLaMA 3.3 70B
- ✅ Streamlit-powered frontend

---


## 🛠️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/dhanunjairam/Crewai-Blog-Content-Writter
cd Crewai-Blog-Content-Writter
```


python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

pip install -r requirements.lock


LLM_API_KEY=your_openrouter_api_key


streamlit run app.py


📦 File Structure

.
├── app.py               # Streamlit UI and core logic
├── README.md
├── requirements.lock    # Dependencies with versions
└── .env                 # (Add your API key here)

🔧 Requirements

    Python 3.8+

    OpenRouter API key

    Internet connection

📄 License

This project is licensed under the MIT License.




