# 📊 Project 5: Sales Analytics Dashboard App
⭐ **Portfolio Project: Interactive Data App for Sales Analytics**

---

## 🌍 Language Options | Opções de Idioma
This README is available in two languages:
- 🇺🇸 **English (Primary)**
- 🇧🇷 **Português (Secondary)**

---

## 🇺🇸 English Version

## 📌 Project Overview
This repository contains a **Sales Analytics Dashboard Data App** built with **Python and Streamlit**, designed to deliver a clean, interactive interface for exploring sales indicators and business metrics.

It is structured as a lightweight app that can run locally and uses a local database file for persistence (included in the repository).

---

## 🎯 Goals
- Provide a simple and practical **dashboard experience** for Sales Analytics  
- Practice building a **Data App** using Python (end-to-end)
- Organize a small project with **code + requirements + local database**

---

## ✅ Key Features
- Interactive dashboard interface (Streamlit)
- Business-friendly organization for metrics and indicators
- Local persistence via database file (`.db`)
- Easy setup using `requirements.txt`

---

## 🧱 Project Structure
```

├─ dash_app.py
├─ dash_database.db
├─ requirements.txt
└─ LEIAME.txt

````

---

## 🛠️ Tech Stack
- Python
- Streamlit
- Data analysis libraries (see `requirements.txt`)
- Local database (`.db`)
---

## ▶️ How to Run

### 1) Clone the repository
```bash
git clone https://github.com/Ojuara-e/Project-Dashboard-App.git
````

### 2) Enter the project folder

```bash
cd Project-Dashboard-App
```

### 3) Create and activate a virtual environment (recommended)

**Conda**

```bash
conda create --name dashboardapp python=3.13
conda activate dashboardapp
```

**venv**

```bash
python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
```

### 4) Install dependencies

```bash
pip install -r requirements.txt
```

### 5) Run the app

```bash
streamlit run dash_app.py
```

([GitHub][1])

---

## 📌 Notes

* This is an **educational/portfolio project** focused on practicing dashboard development.
* The database file (`dash_database.db`) is included for convenience and local testing.

## 🧩 Suggested Improvements (Optional)

* Add screenshots/GIFs of the dashboard
* Add a “Metrics Dictionary” describing each KPI
* Export insights to CSV/PDF from the UI
* Add filters: date range, category, region, channel

---

## 🇧🇷 Versão em Português

## 📌 Visão Geral do Projeto

Este repositório contém uma **Data App de Dashboard para Sales Analytics**, desenvolvida em **Python com Streamlit**, com o objetivo de entregar uma interface simples e interativa para análise de indicadores e métricas de negócio.

O projeto foi estruturado para rodar localmente e inclui um arquivo de banco de dados para persistência dos dados no ambiente de teste.
---

## 🎯 Objetivos

* Criar uma experiência prática de **dashboard interativo**
* Praticar desenvolvimento de **Data Apps** em Python (ponta a ponta)
* Organizar um mini projeto com **código + dependências + banco local**

---

## ✅ Funcionalidades

* Interface interativa com Streamlit
* Estrutura amigável para análise de métricas
* Persistência local via arquivo `.db`
* Instalação simples via `requirements.txt`
---

## 📁 Estrutura do Projeto

```
├─ dash_app.py
├─ dash_database.db
├─ requirements.txt
└─ LEIAME.txt
```

---

## 🛠️ Tecnologias

* Python
* Streamlit
* Bibliotecas de análise (ver `requirements.txt`)
* Banco local (`.db`)
---

## ▶️ Como Executar

### 1) Clonar o repositório

```bash
git clone https://github.com/Ojuara-e/Project-Dashboard-App.git
```

### 2) Entrar na pasta

```bash
cd Project-Dashboard-App
```

### 3) Criar e ativar ambiente virtual (recomendado)

**Conda**

```bash
conda create --name dashboardapp python=3.13
conda activate dashboardapp
```

**venv**

```bash
python -m venv venv
# Linux/Mac
source venv/bin/activate
# Windows
venv\Scripts\activate
```

### 4) Instalar dependências

```bash
pip install -r requirements.txt
```

### 5) Rodar o app

```bash
streamlit run dash_app.py
```

---

## 📌 Observações

* Projeto com foco **educacional e de portfólio**
* O arquivo `dash_database.db` está no repositório para facilitar testes locais.
