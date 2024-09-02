To implement the chatbot, we will be using Keras, which is a Deep Learning library, NLTK, which is a Natural Language Processing toolkit, and some helpful libraries. 

How do Chatbots Work?
Chatbots are nothing but an intelligent piece of software that can interact and communicate with people just like humans. Interesting, isn’t it? So now let's see how they actually work.

All chatbots come under the NLP (Natural Language Processing) concepts. NLP is composed of two things:

NLU (Natural Language Understanding): The ability of machines to understand human language like English.

NLG (Natural Language Generation): The ability of a machine to generate text similar to human written sentences.

Project File Structure
After the project is complete, you will be left with all these files. Lets quickly go through each of them. It will give you an idea of how the project will be implemented.

Train_chatbot.py — In this file, we will build and train the deep learning model that can classify and identify what the user is asking to the bot.

Gui_Chatbot.py — This file is where we will build a graphical user interface to chat with our trained chatbot.

Intents.json — The intents file has all the data that we will use to train the model. It contains a collection of tags with their corresponding patterns and responses.

Chatbot_model.h5 — This is a hierarchical data format file in which we have stored the weights and the architecture of our trained model.

Classes.pkl — The pickle file can be used to store all the tag names to classify when we are predicting the message.

Words.pkl — The words.pkl pickle file contains all the unique words that are the vocabulary of our model.
