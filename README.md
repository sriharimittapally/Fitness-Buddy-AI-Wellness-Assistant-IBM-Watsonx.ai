
# 🏋️‍♂️ Fitness Buddy – AI-Powered Health & Wellness Assistant

This project presents **Fitness Buddy**, an AI-powered virtual assistant designed to promote healthy living by providing personalized workout routines, meal suggestions, motivational advice, and habit-building tips. It is implemented using **IBM Watsonx.ai** and the **Granite-3-3-8b-instruct** foundation model in a completely prompt-based, no-code environment.

---

## 🚀 Problem Statement

In today’s fast-paced world, many individuals struggle to maintain a healthy lifestyle due to lack of personalized guidance, time constraints, and inconsistent motivation. Traditional fitness platforms often involve rigid schedules, high costs, or inaccessible support systems.

**Fitness Buddy** addresses this challenge by providing a friendly, intelligent, and accessible virtual coach capable of offering:
- Home workout suggestions
- Nutritious meal ideas
- Daily fitness motivation
- Support for building consistent habits

---

## 🧠 Solution Overview

The assistant is built using **IBM Watsonx.ai Sandbox**, without requiring any training or datasets. Prompt engineering is used to simulate real-world user interaction.

### 🧩 Key Components:
- **Prompt-based input** simulating user queries
- **Granite-3-3-8b-instruct** model used for response generation
- **Watsonx Agent Lab** to configure model behavior
- **No deployment or frontend** (run completely in Watsonx sandbox)

---

## ⚙️ Technologies Used

| Component | Description |
|----------|-------------|
| IBM Watsonx.ai | Foundation model platform for enterprise AI |
| Granite-3-3-8b-instruct | IBM’s LLM used to generate fitness responses |
| Agent Lab | GUI tool to build agent instructions and test prompts |
| Prompt Engineering | Key methodology for response control and behavior |

---

## 📥 Project Setup (How to Replicate)

1. Go to [https://dataplatform.cloud.ibm.com](https://dataplatform.cloud.ibm.com)
2. Log in to your **IBM Watsonx.ai** account
3. Create a new project → Watsonx Agent → Select `granite-3-3-8b-instruct`
4. Set instructions for your agent (see below)
5. Test prompts in the **Agent Preview** panel

### Sample Agent Instructions:
```
You are Fitness Buddy, an AI-powered health and wellness assistant. Your role is to help users maintain a healthy lifestyle by providing personalized workout routines, simple meal ideas, motivational tips, and habit-building suggestions. Be friendly, concise, and supportive in your responses. Avoid suggesting medical treatments or extreme diets. Always promote balanced, safe, and beginner-friendly advice.
```

---

## 💬 Sample Prompts and Responses

### 🔹 Prompt 1:
*"Suggest a 15-minute full-body home workout for a beginner with no equipment."*  
✔️ Response: Provided a structured workout plan including warm-up, bodyweight exercises, and cooldown. Safe and beginner-friendly.

### 🔹 Prompt 2:
*"Give me a high-protein vegetarian dinner idea under 400 calories."*  
✔️ Response: Suggested quinoa-stuffed bell peppers with nutritional balance and preparation steps.

### 🔹 Prompt 3:
*"Motivate me to work out after a long workday."*  
✔️ Response: Delivered motivational reasoning, benefits of small workouts, and encouraging language.

Screenshots available in `/screenshots/`.

---

## 📊 Results Summary

| Prompt Goal                        | Accuracy | Structure | Tone        | Safety |
|-----------------------------------|----------|-----------|-------------|--------|
| Home workout routine              | ✅ High   | ✅ Clear   | ✅ Supportive | ✅ Yes |
| Low-calorie dinner suggestion     | ✅ Exact  | ✅ Recipe  | ✅ Neutral    | ✅ Yes |
| Motivation after long workday     | ✅ Matched| ✅ Natural | ✅ Uplifting | ✅ Yes |

---

## 🔮 Future Scope

- Integration with wearables (e.g., Fitbit, Apple Health)
- Real-time workout video recommendations
- Voice assistant support (Watson Speech-to-Text/Text-to-Speech)
- Multilingual response generation
- Calendar/reminder system for workout scheduling

---

## 📚 References

- [IBM Watsonx.ai Documentation](https://www.ibm.com/docs/en/watsonx)
- [Granite Model Overview – IBM](https://www.ibm.com/blogs/research/2023/05/granite-models-watsonx)
- [Watsonx Agent Lab Guide](https://www.ibm.com/docs/en/watsonx/agent-lab)
- [Prompt Engineering Best Practices](https://github.com/dair-ai/Prompt-Engineering-Guide)

---

## 📸 Screenshots

All screenshots of responses are available in the `/screenshots/` folder and were used in the project report and result slide.

---

## 🙌 Acknowledgements

Thanks to IBM for providing free Watsonx sandbox access and Granite model support, enabling students to build real-world AI applications without requiring model training or infrastructure setup.

---

## 📄 License

This project is for academic use only. No data was collected or stored. All AI outputs are generated in IBM Watsonx and tested via prompt-based interaction.
