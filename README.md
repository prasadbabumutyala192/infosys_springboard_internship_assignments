# 🌟 Infosys Springboard Internship Assignments  

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![LangChain](https://img.shields.io/badge/LangChain-AI_Framework-orange)](https://www.langchain.com/)
[![Google Flan-T5](https://img.shields.io/badge/Model-FLAN--T5--Large-green)](https://huggingface.co/google/flan-t5-large)
[![Status](https://img.shields.io/badge/Status-Completed-success)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)

---

## 🧾 Overview

This repository contains the complete set of *AI assignments* developed as part of the *Infosys Springboard Internship Program (AI/ML Track)*.  
It includes step-by-step implementations progressing from *LangChain basics* to *multi-agent orchestration systems*.

---

## 📁 Repository Structure

| File | Description | Milestone |
|------|--------------|------------|
| 🧩 *1st_asg_basic_io.py* | Implementation of a basic text-to-text generation pipeline for input/output interaction. | Milestone 1: LangChain Basics |
| 📄 *1st_asg_rag1.py* | Basic Retrieval-Augmented Generation (RAG) project for querying an unstructured document. | Milestone 1: LangChain Basics |
| 🤖 *2nd_assignment_shoppingagent.py* | Implementation of a specialized shopping agent for ingredient and pricing logic. | Milestone 2/3: Agent Development |
| 🧠 *3rd_asg_meal_planner_agent.py* | The final multi-agent orchestration code for an AI-based meal planner. | Milestone 3/4: Final Framework |
| 🍽 *MealsDB.csv* | Structured dataset containing meal and ingredient information. | Data Source |

---

## 📚 Assignment Details

<details>
<summary>🧠 <strong>Assignment 1: LangChain Fundamentals (Milestone 1)</strong></summary>

### 🔹 1. Basic I/O Interaction — 1st_asg_basic_io.py

*Goal:*  
Build a simple text generation pipeline to demonstrate input/output handling with a language model.

*Key Steps:*
- Setup the *Flan-T5 Large* model.
- Create and apply a *Prompt Template*.
- Implement a *Chain (LLMChain)* for automated text generation.
  
*Concepts Covered:*  
LLMs • Prompt Templates • LLMChain • LangChain Basics

---

### 🔹 2. Basic Retrieval-Augmented Generation (RAG) — 1st_asg_rag1.py

*Goal:*  
Implement a *RAG pipeline* to answer questions using unstructured data.

*Key Steps:*
- Load a document (PDF or text) using PyPDFLoader.
- Split data with RecursiveCharacterTextSplitter.
- Generate embeddings and store in a *Vector Store*.
- Create a *Retrieval Chain* for context-aware responses.

*Concepts Covered:*  
Document Loaders • Text Splitters • Vector Stores • Retrievers • RAG Architecture

</details>

---

<details>
<summary>⚙ <strong>Assignment 2: Specialized Agent Development (Milestone 2)</strong></summary>

### 🔹 3. Shopping Agent — 2nd_assignment_shoppingagent.py

*Goal:*  
Design a specialized *Shopping Agent* that identifies required ingredients and optionally finds prices or availability.

*Features:*
- Takes meal planner outputs (recipe or meal list).
- Determines what ingredients are missing or need purchasing.
- Can be extended with tools for:
  - Price estimation
  - Store data fetching

*Concepts Covered:*  
Custom Agent Design • Tool Integration • Decision Logic • Agent Framework

</details>

---

<details>
<summary>🤝 <strong>Assignment 3: Multi-Agent Meal Planner Orchestration (Milestone 3/4)</strong></summary>

### 🔹 4. Meal Planner Orchestration — 3rd_asg_meal_planner_agent.py

*Goal:*  
Develop a complete *multi-agent AI system* that coordinates multiple agents to create a personalized meal plan.

*Features:*
- Integrates *Meal Planner, **Shopping, and **Data Agents*.
- Uses *LangChain Tools* for cross-agent communication.
- Reads data from MealsDB.csv for meal and ingredient info.
- Demonstrates *Agent Orchestration Framework* concepts.

*Concepts Covered:*  
Multi-Agent Systems • Task Delegation • Context Sharing • Orchestration

</details>

---

## 🧠 Key Learnings

| Concept | Description |
|----------|--------------|
| *LangChain Basics* | Learned to create LLM Chains and manage prompts. |
| *RAG Systems* | Integrated document retrieval for contextual answers. |
| *Agents & Tools* | Built specialized agents that perform targeted tasks. |
| *Multi-Agent Orchestration* | Coordinated multiple agents to achieve a single objective. |

---

## 🍽 Dataset Used

*File:* MealsDB.csv  
*Contents:*
- Meal Names  
- Ingredients  
- Nutritional Information  
- Meal Categories  

Used by the Meal Planner and Shopping Agents for meal and ingredient recommendations.

---

## ⚙ Tech Stack

| Technology | Purpose |
|-------------|----------|
| 🐍 *Python 3.10+* | Base programming language |
| 🔗 *LangChain* | Agent and chain framework |
| 🧮 *Google Flan-T5 / Generative AI* | Language model backbone |
| 🧠 *Vector DB (FAISS / Chroma)* | Document retrieval |
| 📊 *pandas / sqlite3* | Data processing and storage |

---

## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/<your-username>/infosys_springboard_internship_assignments.git
cd infosys_springboard_internship_assignments

# Install dependencies
pip install langchain langchain-community langchain-core google-generativeai pandas

# Run an assignment file
python 1st_asg_basic_io.py
# or
python 3rd_asg_meal_planner_agent.py
