# FUTURE_ML_03
This repository will contain code for developing a chatbot for customer support
# Customer Support Chatbot - Model Development & Application

This repository details the model development phase of a customer support chatbot, built using Large Language Models (LLMs) and designed for efficient customer interaction.

## Project Summary

This project demonstrates the end-to-end process of creating a functional customer support chatbot. We focused on training a `T5ForConditionalGeneration` model ("t5-small") using the "bitext/Bitext-customer-support-llm-chatbot-training-dataset" from Hugging Face. The trained model achieved an evaluation loss of 0.288, indicating strong learning and generalization.

To provide a complete application, we also developed a FastAPI backend and a React.js/Tailwind CSS frontend. This enables users to interact with the chatbot through a user-friendly web interface.

## Key Components

* **Model Training:**
    * Utilized Hugging Face's `transformers` and `torch` libraries.
    * Trained on the "bitext/Bitext-customer-support-llm-chatbot-training-dataset".
    * Achieved an evaluation loss of 0.288.
    * Deployed on Hugging Face Spaces: [HaliG/customer-support-chatbot](https://huggingface.co/HaliG/customer-support-chatbot)
* **Backend (FastAPI):**
    * Handles API requests and chatbot logic.
    * Manages communication between the frontend and the model.
    * Repository: [https://github.com/Hali57/customer-support-backend.git](https://github.com/Hali57/customer-support-backend.git)
* **Frontend (React.js + Tailwind CSS):**
    * Provides a user interface for interacting with the chatbot.
    * Designed for a clean and responsive user experience.
    * Repository: [https://github.com/Hali57/customer-support-frontend.git](https://github.com/Hali57/customer-support-frontend.git)

## Getting Started

To run the full application locally, please clone all three repositories:

1.  Model Development Code: [https://github.com/Hali57/FUTURE_ML_03.git](https://github.com/Hali57/FUTURE_ML_03.git)
2.  Backend: [https://github.com/Hali57/customer-support-backend.git](https://github.com/Hali57/customer-support-backend.git)
3.  Frontend: [https://github.com/Hali57/customer-support-frontend.git](https://github.com/Hali57/customer-support-frontend.git)

Follow the individual README files within each repository for setup and execution instructions.

## Collaboration & Contributions

This project is open for collaboration and improvement. If you have ideas for enhancements, optimizations, or bug fixes, feel free to contribute! I welcome pull requests and suggestions.

Let's work together to make this chatbot even better!

## Core Components of an AI Customer Support Chatbot
|Component	|Function|
|-----------|---------|
|Natural Language Processing (NLP)|	Understands and processes user input|
|Intent Recognition|	Classifies the purpose of the message|
|Response Generation	|Retrieves or generates an appropriate response|
|Memory & Context Handling	|Remembers past interactions for a better experience|
|Multi-Channel Deployment|	Works on web, mobile, WhatsApp, Telegram, etc.|
|Analytics & Feedback Loop	|Learns from user feedback and improves over time|



