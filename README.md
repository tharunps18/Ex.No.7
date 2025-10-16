# Ex.No.7 – Develop a Prompt-Based Application using ChatGPT

**Date:*16/10/2025*  
**Register No.:*212224110055*  

---

## Title
Development of a Prompt-Based Application Tailored to Personal Needs using ChatGPT

---

## Aim
To develop a prompt-based application using ChatGPT that can act as a personal productivity assistant.  
The purpose of this experiment is to demonstrate how to design and use prompt-based interactions with a large language model (LLM) to organize daily tasks, schedule reminders, generate wellness suggestions, and respond to general user queries.  
This exercise also focuses on showing the progression from simple prompts to more advanced prompt designs, thereby illustrating the adaptability and capability of modern AI-based tools.

---

## Objectives
1. To understand the concept and importance of prompt-based applications.  
2. To learn how to design effective prompts for specific user needs.  
3. To explore how large language models can assist in managing real-world daily activities.  
4. To implement a prototype of a personal productivity assistant using ChatGPT.  
5. To develop creativity and practical problem-solving skills using AI tools.  
6. To simulate adaptive responses and preference learning using basic memory or contextual prompts.

---

## Tools and Technologies Required
- ChatGPT (Version 4 or 5)  
- OpenAI Playground or API  
- Optional: Python or Node.js environment for simulation  
- JSON or simple text file for storing task and preference data  
- Any text editor or IDE (e.g., VS Code)  
- Internet connection for API-based communication  

---

## Theory

### Introduction to Prompt-Based Applications
A prompt-based application uses the concept of **prompt engineering** to instruct a large language model (LLM) to perform specific tasks.  
Instead of programming the system using traditional coding logic, developers interact with the AI through carefully designed **natural language instructions**, known as prompts.  

Such systems can dynamically adapt, interpret user intent, and perform actions such as scheduling, answering questions, generating content, and managing productivity.

---

### Importance of Prompt Engineering
Prompt engineering is the process of crafting and refining queries to obtain accurate and meaningful results from large language models.  
The effectiveness of any prompt-based system depends on:
- The clarity of the prompt.  
- The context provided to the model.  
- The inclusion of role-based or scenario-based instructions.  
- The ability to modify prompts dynamically based on user feedback.

Through proper prompt engineering, we can guide the model to behave like a **virtual personal assistant**, helping in both personal and professional tasks.

---

### Role of ChatGPT in Application Development
ChatGPT, developed by OpenAI, is an advanced conversational AI model trained on large-scale datasets.  
It can understand and generate human-like responses, reason contextually, and process natural language instructions.  
When integrated into a structured application with well-designed prompts, ChatGPT can act as a virtual productivity assistant capable of:
- Managing tasks and reminders.  
- Giving wellness tips and motivational advice.  
- Answering general queries.  
- Adapting to user preferences over time.  

---

## Problem Statement
In the modern era, individuals handle numerous tasks daily, ranging from professional commitments to personal goals. Managing these effectively often becomes challenging.  
A personal productivity assistant that operates through natural conversation can help streamline tasks and enhance time management.

The goal of this experiment is to design a **prompt-based assistant** that interacts conversationally and helps users manage their daily routine efficiently.

---

## Procedure

### Step 1 – Define the Core Requirements
The first step is to outline what functionalities the personal productivity assistant must perform.  
The essential features include:
- Adding, editing, and deleting daily tasks.  
- Scheduling reminders and meetings.  
- Providing health and wellness suggestions.  
- Answering general questions.  
- Learning user preferences and adjusting future recommendations accordingly.

---

### Step 2 – Identify and Construct Suitable Prompts
Each feature is represented by a specific type of prompt.  
Examples are as follows:

| Feature | Example Prompt | Purpose |
|----------|----------------|----------|
| Task Manager | "Remind me to finish the lab report at 6 PM." | Add and organize daily tasks. |
| Scheduler | "Schedule a meeting with the project team at 4 PM tomorrow." | Manage and allocate time slots. |
| Wellness Tip | "Suggest a wellness activity for today." | Provide health or motivational advice. |
| Query Response | "What is the best way to stay focused while studying?" | Give general guidance and information. |
| Adaptation | "I prefer to get reminders in the morning." | Adjust settings based on preferences. |

---

### Step 3 – Simulate Natural User Interaction
The assistant can be simulated using a **command-line interface (CLI)** or a simple **chat interface**.  
An example CLI simulation in Python is as follows:

```python
while True:
    user_input = input("You: ")
    if user_input.lower() in ["exit", "quit"]:
        break
    response = chatgpt_api(user_input)
    print("Assistant:", response)
```

### Step 4 – Collect Feedback and Adapt

```python
# The assistant should be able to record user preferences or feedback.
# Example: Storing and adapting based on user behavior.

# Simulated memory structure using a Python dictionary.
user_preferences = {
    "preferred_time": "evening",
    "wellness_interest": "fitness",
    "reminder_frequency": "daily"
}

def update_preferences(key, value):
    """Update the user preferences dynamically."""
    user_preferences[key] = value
    print(f"Preference updated: {key} → {value}")

def get_suggestion():
    """Provide suggestions based on stored preferences."""
    if user_preferences["preferred_time"] == "evening":
        print("You usually prefer evening tasks. Would you like to schedule this for 6 PM?")
    if user_preferences["wellness_interest"] == "fitness":
        print("Since you’re interested in fitness, here’s a quick wellness tip: Try a 10-minute walk now.")

# Example Usage
get_suggestion()
update_preferences("preferred_time", "morning")
get_suggestion()

```
--------------------------------------------------------------
## Output website:

link: https://kindred-day-guide.lovable.app

--------------------------------------------------------------

 -------------------------------------------------------------
### Conclusion: Prompt-Based Application using ChatGPT
 -------------------------------------------------------------

"""
In this experiment, a prompt-based personal productivity assistant 
was successfully designed and simulated using ChatGPT.

The project demonstrated how large language models can understand 
and respond to natural language prompts for various real-life tasks 
such as task management, scheduling, and wellness recommendations.

Through progressive prompt engineering, the assistant was able to:
1. Manage daily tasks and reminders conversationally.
2. Provide context-aware wellness tips.
3. Adjust its behavior based on user preferences and feedback.
4. Simulate adaptive learning through memory-like structures.

This experiment helped students develop skills in:
- Designing structured prompts for LLMs.
- Applying creativity to AI-driven problem-solving.
- Understanding contextual and adaptive AI responses.
- Exploring the practical applications of generative AI in everyday life.

Hence, the experiment achieved its objectives and successfully demonstrated 
How prompt-based systems can serve as intelligent assistants 
that enhance productivity, personalization, and user engagement.
"""
 -------------------------------------------------------------
