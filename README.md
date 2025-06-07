# FoodGO – AI-Powered Nutrition Assistant
FoodGO is an intelligent web application built with Streamlit, LangChain, and the USDA FoodData Central API, designed to analyze nutritional values of food items and recipes. It also features a conversational AI powered by LLaMA 3.2 via Ollama to answer health and nutrition-related queries with context-aware insights.

## 🚀 Features
- 🧠 Nutritional Analysis from USDA FoodData Central API
- 🗣️ Conversational Mode with AI (LLaMA 3.2) for dietary questions
- ⚖️ Supports custom quantity scaling for nutrition values
- 📊 Interactive visual charts for macronutrients
- 🧾 Allows both dropdown selection and free-text input
- 💬 Retains and displays chat history for context-rich conversations
- 💡 Built-in error handling and response feedback
- 📁 All conversations are saved to local history (folder: conversations/)

## 🛠️ Tech Stack
- Frontend: Streamlit
- Backend: Python (requests, matplotlib, re, datetime)
- LLM Integration: LangChain + Ollama (llama3.2)
- Nutrition Source: USDA API (FDC)
- Data Visualization: Matplotlib

## 📂 File Structure
bash
```
FoodGO/
├── chatbot_foodgo.py       # Main application
├── requirements.txt        # Dependencies
├── conversations/          # Stores past chat logs
├── README.md               # (You are here)
```

## 📦 Setup Instructions
### Install Dependencies

bash
```
pip install -r requirements.txt
```
### Run the App

bash
```
streamlit run chatbot_foodgo.py
```

### Access It
Open in browser: http://localhost:8501

### Optional: Modify API_KEY
Replace the API_KEY in chatbot_foodgo.py with your own from USDA FoodData Central

## 📌 Example Use Cases
- “How much protein is in 2 servings of grilled salmon?”
- “Compare the nutrition of quinoa vs white rice.”
- “Is oatmeal good for people with hypothyroidism?”
- “What are good food sources of zinc and fiber?”

## 👩‍🔬 Powered By
- 🧠 Ollama LLaMA 3.2 for AI conversation
- 📊 USDA FoodData Central API for food nutrition
- 🌐 LangChain for LLM orchestration and prompt engineering



