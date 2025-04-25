# Fine-Tune-Sticker-Website-Chatbot
A lightweight AI-powered chatbot leveraging Google’s Gemini and ChromaDB to deliver fast, accurate, multilingual support for sticker e-commerce customers.
Fine-Tune Sticker Website Chatbot

A lightweight AI-powered chatbot leveraging Google’s Gemini and ChromaDB to deliver fast, accurate, multilingual support for sticker e-commerce customers.



1. Model Initialization: Sets up and configures Google's Gemini generative model to effectively interpret and respond to customer queries related to sticker products. This initialization ensures the model is ready to handle various types of questions in real time.

2. Knowledge Base Definition: Establishes a small internal collection of documents that describe the product catalog, material quality, customization workflow, order processing steps, and shipping/delivery pricing. These documents act as a domain-specific source of truth for the chatbot.

3. Embedding Function: Implements a mechanism using ChromaDB in combination with Gemini’s text embedding model. This component transforms each document into a high-dimensional vector, enabling the chatbot to perform semantic searches and identify the most relevant information based on the user's input.

4. Query Handling and Response Generation: Builds intelligent responses by retrieving the most appropriate document snippet, constructing a prompt, and using Gemini to formulate a response. The chatbot supports both Arabic and English, replies in the same language as the query, and strictly limits answers to topics relevant to the sticker business, such as design, pricing, delivery, and customization.

