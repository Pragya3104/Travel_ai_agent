
# 🌍 Travel Planner Agent

An AI-powered assistant built using **IBM watsonx.ai Agent Lab** that helps users plan trips efficiently, offering destination suggestions, itinerary building, weather updates, and more—all through natural language interaction.

---

## 🚀 Overview

The **Travel Planner Agent** is designed to assist users with personalized travel planning using a conversational interface. Built using the IBM watsonx Agent Lab, it leverages large language models and custom tools to streamline trip preparation for solo, family, and business travelers.

---

## 🛠️ Agent Configuration

- **Framework**: LangGraph  
- **Architecture**: ReAct  
- **Model**: `granite-3-3-8b-instruct`  
- **Max Tokens**: `2000`  
- **Temperature**: `0.7`  
- **Top P**: `0.9`  
- **Frequency Penalty**: `0.5`  
- **Presence Penalty**: `0.3`  

### 🧠 Agent Instructions

> You are a helpful assistant that uses tools to answer questions in detail.  
> When greeted, say:  
> **"Hi, I am watsonx.ai Travel Planner Agent. How can I help you plan your trip today?"**

---

## 📦 Features

- 🧭 Destination discovery based on user preferences
- 🗓️ Day-wise itinerary planning
- ✈️ Flight and hotel recommendation tool integration *(optional)*
- 🌦️ Weather forecast for planned travel locations
- 💰 Budget-based travel suggestions
- 📍 Local attractions and activity tips

---

## 🖥️ Deployment

This agent is deployed and managed via **IBM watsonx.ai Agent Lab**:

🔗 [IBM watsonx.ai](https://dataplatform.cloud.ibm.com)

To deploy:
1. Open IBM watsonx Agent Lab.
2. Import configuration and set tools if needed.
3. Test agent behavior using the preview panel.
4. Click **Deploy** once verified.

---

## 📂 Folder Structure

```
travel-planner-agent/
├── README.md
├── agent-config.md
├── tools/
│   └── flight_tool.py (example)
├── images/
│   └── screenshot-ui.png
└── .gitignore
```

---

## 🔧 How to Contribute

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature-name`
3. Commit your changes.
4. Push and create a pull request.

---

## 📄 License

This project is for educational and non-commercial use only. Contact the author for other usage.

---

## 👤 Author

**Pragya Jha**  
🎓 B.Tech CSE (Data Science & AI), 3rd Year  

---

## 💡 Inspiration

This project was created to explore the capabilities of IBM watsonx for building intelligent, conversational travel assistants with practical utility and real-world integration potential.
