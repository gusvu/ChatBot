# ChatBot

I am well versed in base python, however I am not familiar with many packages. So I decieded to follow a project with sorce code creating a chatbot. https://data-flair.training/blogs/python-chatbot-project/ I have added a screenshot in the repository to show an example of how it works. 


Intents.json – The data file which has predefined patterns and responses.
train_chatbot.py – In this Python file, we wrote a script to build the model and train our chatbot.
Words.pkl – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
Classes.pkl – The classes pickle file contains the list of categories.
Chatbot_model.h5 – This is the trained model that contains information about the model and has weights of the neurons.
Chatgui.py – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.


If you would like to run it on your own follw my directions:
1) download all the files into a folder (The screenshot is not nessicary to download).
2) Change your directory to where thr files are located, and open a python shell. 
3) First run `python train_chatbot.py` to train the model.
4) Next run `python chatgui.py` to open the GUI window.

Hope you enjoy :)
