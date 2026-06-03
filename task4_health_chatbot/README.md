# Task 4: General Health Query Chatbot

## Overview

This project was developed as part of the AI/ML Engineering Internship at DevelopersHub Corporation.

The objective of this project is to build a health information chatbot that can answer general health-related questions using Google's Gemini Large Language Model (LLM). The chatbot uses prompt engineering techniques to generate clear and user-friendly responses while incorporating safety measures to prevent harmful medical advice.

## Project Objective

The chatbot is designed to:

* Answer general health-related questions
* Provide clear and easy-to-understand explanations
* Demonstrate prompt engineering techniques
* Integrate with a Large Language Model (Gemini API)
* Apply safety filters for responsible AI usage

## Technologies Used

* Python
* Google Gemini API
* Jupyter Notebook
* python-dotenv
* Prompt Engineering

## Project Structure

task4_health_chatbot/
│
├── Health_Chatbot.ipynb
├── README.md
├── requirements.txt
├── .env
└── .gitignore


## Features

### Health Information Assistance

The chatbot provides educational health information on common medical topics such as:

* Sore throat
* Flu prevention
* Dehydration
* Nutrition
* General wellness

### Prompt Engineering

A structured system prompt is used to guide the model's behavior and ensure responses remain:

* Informative
* Friendly
* Easy to understand
* Appropriate for general audiences

### Safety Filters

The chatbot includes safety mechanisms to avoid potentially harmful responses.

Examples of restricted topics include:

* Self-harm related requests
* Medication dosage recommendations
* Requests to stop prescribed treatments
* Dangerous medical instructions

When such topics are detected, the chatbot encourages users to consult qualified healthcare professionals.

## Model Configuration

The project uses Google's Gemini model through the Gemini API.

Example configuration:

```python
genai.configure(api_key=api_key)

model = genai.GenerativeModel(
    "gemini-2.5-flash"
)
```

## Example Questions

Example user queries:

1. What causes a sore throat?

2. How can I prevent the flu?

3. What are common symptoms of dehydration?

Example restricted query:

* Should I stop taking my prescription medication?

### Safety Response Example

Please consult a qualified healthcare professional for medical advice regarding prescribed treatments.


## Implementation Workflow

1. Load Gemini API credentials securely
2. Configure the Gemini model
3. Apply prompt engineering instructions
4. Validate user input through safety filters
5. Generate a response using Gemini
6. Display the response to the user

## Key Learnings

Through this project, the following skills were developed:

* Large Language Model (LLM) integration
* API-based application development
* Prompt engineering
* Responsible AI design
* Safety-aware chatbot development
* Python-based conversational systems

## Results

The chatbot successfully:

* Integrated with the Gemini API
* Generated health-related informational responses
* Applied prompt engineering principles
* Implemented safety restrictions for sensitive topics
* Provided a simple conversational interface for users

## Internship Information

Developed as part of the:

**AI/ML Engineering Internship**
**DevelopersHub Corporation**

## Author

**Ibrar Ahmad**