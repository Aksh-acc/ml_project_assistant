# 🤖 ML Project Assistant

The **ML Project Assistant** is a smart assistant built using [CrewAI](https://docs.crewai.com/) and powered by [Groq API](https://console.groq.com/). It helps data scientists and ML engineers by understanding problem statements or model requirements and generating insightful guidance. The results are automatically compiled into a neat `report.md` file.

---

## 🚀 Features

- Accepts user input describing an ML problem or model goal.
- Uses CrewAI agents and tasks to process the input.
- Executes model selection or analysis using Groq's blazing-fast LLMs.
- Outputs a detailed report in `report.md`.

---

## 📦 Requirements

- Python 3.10+
- `uv` (a faster alternative to pip/venv)
- A valid [Groq API key](https://console.groq.com/)
- Internet connection (to access Groq LLMs)

---

## 🛠 Installation & Setup

1. **Clone the Repository**

```bash
git clone https://github.com/yourusername/ml_project_assistant.git
cd ml_project_assistant

2. **Create Virtual Environment using uv**
uv venv

3. Activate the Environment

 On Windows:
.venv\Scripts\activate

 On macOS/Linux:
source .venv/bin/activate

4. Add your Groq API Key

Create a .env file in the root directory and add:
GROQ_API_KEY=gsk_your_actual_key_here
```
##📎 Useful Resources

  -🌐 CrewAI GitHub: https://github.com/joaomdmoura/crewai

  -  📚 CrewAI Docs: https://docs.crewai.com

   - ⚡ Groq Console: https://console.groq.com

  -📖 Groq API Documentation: https://console.groq.com/docs

  -  🚀 UV by Astral: https://github.com/astral-sh/uv

##Contributing

Contributions, feature requests, and bug reports are welcome!
Please open an issue or submit a pull request to improve the assistant.

##Acknowledgements

Big thanks to:

    CrewAI for the incredible agent framework.

    Groq for blazing-fast inference capabilities.

    The open-source community 🫶
