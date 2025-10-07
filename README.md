# 🧠 AI Meal Planner (Infosys Springboard Project)

This project is an **AI-powered meal planning system** developed in **Google Colab** as part of the Infosys Springboard assignment.  
It uses a **multi-agent architecture** to generate personalized meal plans based on user preferences, health goals, allergies, and budget constraints.

---

## Features
- **Multi-Agent System** – Includes Admin, Planner, Researcher, Writer, and Editor agents that collaborate to build meal plans.  
- **Personalized Planning** – Creates meal plans customized to dietary goals, allergies, and budget preferences.  
- **Food Data Integration** – Connects to APIs like *TheMealDB*, *USDA*, or *CalorieNinjas* for nutritional and recipe data.  
- **Persistent Memory** – Stores previous user inputs and meal recommendations in JSON files.  
- **Interactive Feedback** – Adapts meal suggestions based on user feedback or new constraints.

---

##  How to Run

### Option 1: Run in Google Colab
1. Open the `.ipynb` notebook in **Google Colab**.  
2. Mount your Google Drive when prompted.  
3. Upload any necessary datasets such as `MealsDB.csv`.  
4. Run all cells sequentially.  
5. Follow on-screen prompts to generate your personalized meal plan.

### Option 2: Run Locally
1. Download the notebook file (`.ipynb`).  
2. Open it in **Jupyter Notebook**.  
3. Install the required Python packages:
   pip install pandas requests tabulate numpy
