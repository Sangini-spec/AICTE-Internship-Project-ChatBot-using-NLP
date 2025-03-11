# AICTE-Internship-Project-ChatBot-using-NLP
As an intern of Edunet foundation under collaboration with AICTE , I worked on basics of NLP so as to implement a chatbot using NLP and Logistic Regression with streamlit for frontend.


# Implementation of a ChatBot using NLP

## Overview
This project is a simple chatbot implemented using **Natural Language Processing (NLP)** techniques. The chatbot is built with the **NLTK** library and **Logistic Regression** for text classification. It processes user input and responds based on predefined intents stored in a JSON file.

For the frontend, **Streamlit** is used to provide an interactive and user-friendly interface. The chatbot uses an `intents.json` file, which contains structured data with tags, patterns, and responses to generate appropriate replies.

## Features
- **Natural Language Processing**: Utilizes NLTK for tokenization and text preprocessing.
- **Intent-based Responses**: Uses an `intents.json` file to match user queries with predefined responses.
- **Machine Learning Model**: Implements Logistic Regression for intent classification.
- **Interactive UI**: Built using Streamlit to provide a simple and engaging chatbot experience.

## Technologies Used
- **Python**
- **NLTK (Natural Language Toolkit)**
- **Logistic Regression**
- **Streamlit**
- **JSON (for storing intents)**

## How It Works
1. The chatbot loads the `intents.json` file, which contains various intent tags, user patterns, and corresponding responses.
2. User input is tokenized and preprocessed using **NLTK**.
3. The Logistic Regression model classifies the intent of the input.
4. Based on the classified intent, the chatbot selects a suitable response from the `intents.json` file.
5. The response is displayed in the **Streamlit** interface.

## Installation & Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/Sangini-spec/chatbot-nlp.git
   cd chatbot-nlp
   ```
2. Install dependencies:
   ```sh
   pip install nltk streamlit scikit-learn
   ```
3. Run the chatbot using Streamlit:
   ```sh
   streamlit run chatbot.py
   ```

## File Structure
```
main/
│-- ImplementationofChatBot.ipynb   #Source code for the chatbot        
│-- README.md       
│-- chatbot.py                # Main chatbot script (Streamlit frontend)
│-- intents.json     # JSON file containing intents, patterns, and responses
```

## Future Enhancements
- Implement **Deep Learning** models for improved accuracy.
- Enhance the chatbot's **Natural Language Understanding (NLU)** capabilities.
- Add **Database Integration** for storing and retrieving user conversations.
- Deploy the chatbot as a **web-based service**.

## Contributions
Feel free to contribute by improving the chatbot, fixing bugs, or adding new features. Fork the repository, make changes, and submit a pull request.

## Conclusion
I got to learn a lot about artificial intelligence and specially its implementation from scratch through this internship. I would like to thank all the recruiters and seniors also the government for giving this oppurtunity to young scholars so that we can get to know AI from very close .
