# ai-chatbot
AI chatbot using Python and NLP
# AI Chatbot

This is a simple AI chatbot built using Python.

## Features
- Simple AI chatbot
- Text-based conversation
- Easy to run

## Technologies Used
- Python
- NLP basics

## How to Run

1. Install Python
2. Run the file
3. import random

responses = {
    "hello": ["Hi there!", "Hello!", "Hey!"],
    "how are you": ["I am fine!", "Doing great!", "All good!"],
    "bye": ["Goodbye!", "See you later!", "Bye!"]
}

print("AI Chatbot: Hello! Type 'bye' to exit.")

while True:
    user = input("You: ").lower()

    if user == "bye":
        print("AI Chatbot:", random.choice(responses["bye"]))
        break
    elif user in responses:
        print("AI Chatbot:", random.choice(responses[user]))
    else:
        print("AI Chatbot: I don't understand that.")

python chatbot.py
