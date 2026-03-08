<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=30&duration=3000&pause=1000&color=58A6FF&center=true&vCenter=true&width=700&lines=Hello%2C+I'm+Mateus+C%C3%A2ndido;Computer+Engineering+Student;Python+Backend+Developer;AI+%2B+Data+Projects" />
</h1>

<p align="center">
  <a href="mailto:matturushihara@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-matturushihara@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
  <a href="https://www.linkedin.com/in/mateus-c%C3%A2ndido-05b412265/">
    <img src="https://img.shields.io/badge/LinkedIn-Mateus%20C%C3%A2ndido-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
</p>

---

#  About Me

 Computer Engineering Student
 Backend Developer focused on **Python**
 Building **AI-powered applications**
 Interested in **Data Analysis and APIs**
 Experience with **Django, FastAPI, Flask and PostgreSQL**

---

# Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=python,django,flask,fastapi,postgres,react,tailwind,git,github,linux,vscode,pandas" />

</div>

---

#  GitHub Stats

<div align="center">

<img height="170em" src="https://github-readme-stats.vercel.app/api?username=Mateus-Candido-do-Nascimento&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true"/>

<img height="170em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mateus-Candido-do-Nascimento&layout=compact&langs_count=7&theme=tokyonight"/>

</div>

---

#  Main Project

## LifeNavigator AI

**AI agent that simulates financial and career decisions for people considering public sector jobs in São Paulo.**

### What it does

* Simulates financial scenarios for people considering **public sector jobs**
* Compares **public salaries vs current private salary**
* Calculates **cost of living viability in São Paulo**
* Answers questions like:

Example queries

• "Vale a pena fazer concurso de professor ganhando R$5k?"
• "Quanto ganha um médico no setor público de SP?"
• "Consigo viver bem em SP com R$4.000?"

---

### AI Architecture

```
Frontend (React)
      ↓ POST /api/chat
Django REST Framework
      ↓
guardrails.py       → safety validation
intent_service.py   → intent detection using Groq
data_service.py     → real data lookup with pandas
prompt_builder.py   → few-shot prompt construction
groq_service.py     → analysis generation with Llama 3.3 70B
      ↓
JSON Response
```

---

### ⚙️ Tech Stack

| Layer    | Technology                     |
| -------- | ------------------------------ |
| Frontend | React + Vite + Tailwind        |
| Backend  | Django + Django REST Framework |
| Database | PostgreSQL                     |
| AI       | Groq (Llama 3.3 70B)           |
| Data     | pandas + public datasets       |

---

###  Datasets

**Public Salaries São Paulo**

* 30,000 records of active public employees (2023)
* filtered and proportionally sampled by department

**Cost of Living São Paulo**

* 57 items collected from **Numbeo (March 2026)**
* values normalized in **BRL**

---

### 📁 Project Structure

```
LifeNavigatorAI/
├── backend/
│   ├── chat/
│   │   ├── models.py
│   │   ├── views.py
│   │   └── services/
│   │       ├── data_service.py
│   │       ├── intent_service.py
│   │       ├── prompt_builder.py
│   │       ├── groq_service.py
│   │       ├── guardrails.py
│   │       └── prompts/
│   │           ├── system_prompt.txt
│   │           └── few_shot_examples.txt
│   ├── datasets/
│   │   ├── salarios_limpo.csv
│   │   └── custo_vida_sp_numbeo.csv
│   └── requirements.txt
└── frontend/
    └── src/
        └── App.jsx
```

---

# 📚 Currently Studying

* Data Structures in Python
* AI Agents and Prompt Engineering
* Backend Architecture
* Data Analysis with Pandas

---

# 📈 Activity Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Mateus-Candido-do-Nascimento&theme=tokyo-night"/>

</div>

---

# 🐍 Contribution Snake

<p align="center">
<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake.svg"/>
</p>

---

# 🌐 Connect With Me

<p align="center">

<a href="https://www.linkedin.com/in/mateus-c%C3%A2ndido-05b412265/">
<img src="https://img.shields.io/badge/LinkedIn-Mateus%20C%C3%A2ndido-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<a href="mailto:matturushihara@gmail.com">
<img src="https://img.shields.io/badge/Gmail-matturushihara@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
</a>

</p>

---

⭐ From [Mateus-Candido-do-Nascimento](https://github.com/Mateus-Candido-do-Nascimento)
