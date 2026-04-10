# 📘 Prompt Engineering with LangChain (GenAI Task 1)

## 🚀 Overview
This project demonstrates the fundamentals of **Prompt Engineering** using LangChain.  
It walks through building, structuring, and validating prompts for different use cases like teaching, interviewing, and storytelling.

The notebook progresses from **basic string prompts → reusable templates → structured pipelines**, making it ideal for beginners in Generative AI.

---

## 🧠 Concepts Covered

### 1. Basic Prompt Creation
- Manual string-based prompt generation  
- Example:
```python
"Explain Artificial Intelligence in simple terms for beginners"
```

---

### 2. Prompt Templates
- Using `PromptTemplate` to create reusable prompts  
- Dynamic variable injection

```python
template = "Explain {topic} in simple terms for beginners"
```

---

### 3. Multi-Variable Prompts
- Handling multiple inputs like:
  - topic
  - audience
  - tone

---

### 4. Use-Case Based Templates
Different prompt styles:
- 📖 Teaching mode
- 🎯 Interview questions
- 📚 Story generation

---

### 5. Chat Prompt Templates
- Using `ChatPromptTemplate`
- Structured roles:
  - system
  - user

---

### 6. Input Validation
- Ensures valid values for:
  - audience → beginner/intermediate/expert  
  - tone → formal/casual/fun  
- Defaults applied for invalid inputs

---

### 7. Prompt Generator Function
A reusable function to generate prompts dynamically:
```python
generate_prompt(topic, audience, tone, style)
```

---

### 8. Reusability Testing
- Testing prompts across multiple topics
- Ensures scalability

---

### 9. Complete Prompt Pipeline
End-to-end pipeline:
1. User input  
2. Validation  
3. Prompt generation  
4. Output  

---

## 🛠️ Installation

Install dependencies:
```bash
pip install langchain
pip install langchain-core
```

---

## ▶️ How to Run
1. Open the notebook:
```bash
jupyter notebook GenAI_Task_1.ipynb
```

2. Run cells sequentially

---

## 💡 Example Output
```
Explain AI for beginners in a friendly tone using storytelling style
```

---

## 🎯 Key Learnings
- Prompt structuring is critical in GenAI  
- Templates improve **reusability & scalability**  
- Input validation ensures **robust systems**  
- Pipelines simulate real-world AI applications  

---

## 🔮 Future Improvements
- Integrate with OpenAI / LLM APIs  
- Add UI using Streamlit  
- Expand prompt library  
- Add evaluation metrics for prompt quality  

---

## 👨‍💻 Author
Sarthak Thakur
