# Care-Companion
AI Chatbot for Health

The main aim of this project is to create a chatbot for a given website. Here we are using the Tamil Nadu health website. The data will be scraped from the website and stored in CSV format.
# Method 1 - Using Dialogflow API

We will be using Dialogflow as the main api for building the bot. 
In Dialogflow, an intent will be created, and data that was scraped from the website will be stored as a knowledge base. 

# Method 2 - Using BERT Transformer
We implemented BERT for question-answering and then trained a smart chatbot in interpreting user questions within a user context. It is pre-trained and then fine-tuned on QA datasets (SQuAD) with PyTorch to predict start and end tokens of the answer. As a result, the chatbot captures relevant responses from its context in natural language dialogues.


Then the bot is  deployed.
For the frontend, we are using Tailwind CSS. And we integrated the chatbot deployed in Dialogflow with the website.

![image](https://github.com/user-attachments/assets/eb0910e1-ce60-4aca-8189-1810744bab68)

![image](https://github.com/user-attachments/assets/d3ce2cdf-565b-4403-a2b7-7d052dffb305)

![image](https://github.com/user-attachments/assets/afa671cf-d973-4dcc-9f42-fda40f7cb30d)




