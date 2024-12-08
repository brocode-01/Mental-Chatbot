# Gemini Pro - Mental Health ChatBot

![](https://github.com/ManavGora/Mental-Bro/blob/main/img.png)

## Overview

**Gemini Pro** is an empathetic and supportive chatbot designed to help users with their mental health concerns. It uses Google’s Gemini-Pro AI model to engage in thoughtful conversations, offering coping strategies, resources, and a listening ear to users. This chatbot runs on **Streamlit**, providing an interactive, web-based interface for easy user interaction.

**Key Features**:
- Engages users in compassionate conversations about their mental health.
- Offers non-judgmental, empathetic responses.
- Suggests helpful coping strategies (breathing exercises, journaling, etc.).
- Encourages users to seek professional help when necessary.
- Responses are precise and respectful, without offering medical diagnoses.

## Tech Stack

- **Python 3.10**
- **Streamlit**: Interactive interface for the chatbot.
- **Google Gemini-Pro API**: The backend AI model used for conversation.
- **dotenv**: For managing environment variables (API key).
- **LangChain**: To extend functionalities (if needed).

## Requirements

- Python 3.10
- Conda (for virtual environment management)
- pip (Python package installer)

## Setup and Installation

### 1. Clone the Repository

```bash
git clone <repo-link>
cd new_chatbot
```

2. Set Up the Virtual Environment

Using conda, create and activate a new environment for the project:

```bash
conda create -n new_env python=3.10
conda activate new_env
```

3. Install Required Packages

Run the following command to install all necessary libraries:

```bash
pip install streamlit langchain langchain[community] python-dotenv google-generativeai
```
4. API Key Configuration

To use Google’s Gemini-Pro AI model, you need an API key. Create a .env file in the project root and add your Google API key as follows:

```bash
GOOGLE_API_KEY=your_google_api_key_here
```

5. Run the Application

To start the chatbot, use the following command:

```bash
streamlit run app.py
```

Once the app starts, it will launch a Streamlit interface in your browser where you can interact with the chatbot.

How It Works

- Upon starting the app, the chatbot greets users and invites them to share how they are feeling.
- Users can type their messages in the input field.
- The chatbot provides empathetic responses, suggesting coping strategies and helpful resources without providing medical advice or diagnoses.
- The conversation stays focused on supporting the user while encouraging them to seek professional help if needed.

Example Interaction

User: “I’m feeling really stressed lately.”

Gemini Pro: “I’m really sorry to hear you’re feeling this way. Stress can be overwhelming, but sometimes taking a step back and practicing some deep breathing exercises can help. Would you like me to guide you through one?”

Libraries Used

- Streamlit: For building the web-based interface.
- Google Generative AI (Gemini-Pro): For conversational AI responses.
- dotenv: For environment variable management.
- LangChain: For optional advanced interaction flows.
