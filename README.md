# ChatBot-Carleton
Chatbot using TKinter, tensorflow, NLTK libraries.

## Problem Statement
Most of the tasks these days are carried out using chatbots. Many companies have now incorporated chatbots for various routine services like customer support, information delivery, etc. Business owners want to stay connected to their clients 24/7 but it is virtually impossible. Either there is any task requiring customer support or finding new leads, business owners try to manage these channels of communication throughout their working day and still lag. The chatbot market size is now projected to grow from $2.6 billion in 2020 to $9.4 billion by 2024 at a compound annual growth rate (CAGR) of 29.7%. Hence, the dependency on AI technology like chatbots is growing remarkably.

### Role in current scenario (Covid-19)
Chatbots are reasonably working in dispersing the healthcare information in this current coronavirus crises. It is providing a strong prospective towards curated information. It conveys the response to specific questions in an interactive manner, much more efficiently than conventional online search methods.

## Problem Analysis
CHATBOT is an intelligent piece of software that helps in interacting with the customers, marketing on social network sites and promptly messaging the client. There are two basic types of chatbot models based on how they are built:

1. Retrieval based Chatbots - It uses predefined input patterns and responses to answer appropriately. It is commonly used for making goal-oriented chatbots in the industry.

2. Generative based Chatbots - These are based on sequence-to-sequence neural networks. It needs a large amount of data and it is based on Deep Neural networks.

We have built a retrieval oriented chatbot using deep learning techniques. This chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.
Covid19 - The two most authoritative voices of the pandemic, WHO and CDC, have also included chatbots in their websites to provide latest information on the spread of the disease and its symptoms. Many governments are also launching chatbots to provide validated information to their citizens.

## Working Of ChatBot-Carleton
This chatbot mainly uses the below libraries:

▪ NLTK - for symbolic and statistical natural language processing for English written.

▪ Keras - to enable fast experimentation with deep neural networks, it focuses on being user-friendly, modular, and extensible.

▪ Tensorflow - for dataflow and differentiable programming across a range of tasks.

▪ Pickle - for serializing and de-serializing a Python object structure.

▪ Tkinter – for creating interactive graphical user interface applications.

The software is segregated in parts/classes based on the functionality. The design of this chatbot is mainly divided into 5 parts:
### 1) Import and load the data file

Firstly, a file named as ‘train_chatbot.py’ was generated in which a code was written in order to train the chatbot. Then all the necessary packages were imported like ‘nltk’, ‘keras’, ‘json’ and ‘pickle’ for the chatbot and the variables were initialized.

### 2) Preprocess data

Before making a deep learning model, whole data was pre-processed by breaking it into words. A function named nltk.word tokenize() was used as well as each word in the words list was appended. A list of classes for our tags was also created. After sorting each word, the duplicate words were removed from the list created above. After all the words got converted into its lemma form, a pickle file was created to store the objects which were used later while predicting.

### 3) Create training and testing data

After preprocessing the data, training data was created in which both the input and the output was provided. Input is the pattern and output are the class to which the input pattern belongs.

### 4) Build the model

After training the dataset, a deep neural network was built which was divided into three layers (Keras sequential API was used for this). After training the model for 200 epochs, 100% accuracy was achieved on model.

### 5) Predict the response (Graphical User Interface)

Then, a graphical user interface that predicts the response from the bot was created. The functions to identify the class were implemented and then retrieved a random response from the list of responses. Later, GUI was created using Tkinter library (inbuilt in python) in order to start the interaction with the bot. 6) Run the chatbot
The model was trained by running the train_chatbot.py file. Once, the bot was trained, chatgui.py file was executed to interact with the bot using GUI window.

## Testing
Let us now run all the functionalities one by one and test for some real time cases.

1) After running ‘python train_chatbot.py’ we were successful in training the model.
2) Run ‘python chatgui.py’ to launch GUI of chatbot to chat with the bot.
3) Some responses related to the data on which chatbot is being trained:

## Impact
Microsoft invented new Healthcare Bot service which is especially designed for answering queries of public in this COVID-19 pandemic situation. Microsoft worked with the Centers for Disease Control and Prevention for inculcating this new bot service as a self-screening tool for people who are facing the ambiguity of whether they need treatment for COVID-19 or not.
Among all the Microsoft users, Healthcare Bot service is now handling more than 1 million messages per day approximately from the public concerned about COVID-19 infections.

#### Other impacts are
• Chatbot designed assists the user to answer a query on a particular subject.

• It automatically reduces the manual botheration and speeds up the work.

• It is a high cost-effective software providing relevant information to the users.

• This software accurately solves problem statement thus making the life of a user a lot easier.
