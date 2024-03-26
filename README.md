
# Sahayak: Customer Support ChatBoT
![sahayak2](https://github.com/blackwallpurplestone/acm_project_chatbot/assets/144417599/9093a82c-d6dd-48e6-9fef-21bd27ceea9c)


This project is a chatbot named "Sahayak," which assists users with various health-related inquiries. It utilizes natural language processing (NLP) techniques to understand user queries and provide relevant responses. The chatbot covers a range of topics, including adverse drug reactions, blood pressure monitoring, hospital and pharmacy searches, and lifestyle tips for healthy living.

The project involves several components:
1. **Data Preparation:** It starts by preparing training data from a JSON file containing intents, patterns, and responses related to health-related topics.
2. **Model Training:** A neural network model is trained using the training data to classify user queries into different intents.
3. **Chatbot Implementation:** The chatbot interface is built using the Tkinter library in Python, allowing users to interact with Sahayak by typing messages.
4. **Response Generation:** Upon receiving a message from the user, the chatbot predicts the intent using the trained model and generates an appropriate response based on the detected intent.
5. **User Interaction:** Users can ask questions or seek information about various health topics, and Sahayak responds accordingly, providing relevant advice, guidance, or instructions.
6. **Dynamic Functionality:** The chatbot dynamically handles different scenarios, answering over differen use cases and guiding users through specific processes (e.g., searching for hospitals or pharmacies).

Overall, the project aims to provide users with a helpful and informative chatbot companion for addressing their health-related inquiries and promoting healthy living practices.

## Project Background

This project was made as a part of Data Science Training and Internship Program from ACM Students Chapter IIT Dhanbad 2024-25.


## Demo

https://github.com/blackwallpurplestone/acm_project_chatbot/assets/144417599/4160748c-c737-4383-b46f-1a613d3d45f2


## Problem Statement

**Objective**: To create an interactive Python chatbot that can efficiently handle customer queries, 
thereby enhancing user engagement and satisfaction. 

**Background**: With the growing need for businesses to automate customer service, chatbots have 
become essential. They offer 24/7 assistance, reduce human error, and can handle multiple queries 
simultaneously. While NLP provides a sophisticated approach to understanding user queries in 
natural language, alternative methodologies can also offer valuable solutions for simpler 
applications, focusing on pattern matching or rule-based responses. 

**Scope**: The project will involve developing a chatbot using Python. While the focus is generally on 
NLP capabilities, this version of the project encourages exploring alternative machine learning 
algorithms or rule-based systems that can interpret and respond to user input effectively, without 
the need for complex language understanding. 

**Methodology**: 

• Utilize a JSON dataset for training, comprising various intents and corresponding patterns. 
While the dataset remains the same, the approach to utilizing this data might differ from NLP 
methods. 
• Explore alternative data preprocessing techniques to prepare the input data for the model. 
This may involve simplifying the data into recognizable patterns or keywords that can trigger 
specific responses. 
• Implement an alternative algorithm for intent classification. This could include: 
• Rule-based systems: Developing a set of hardcoded rules that the chatbot uses to 
respond to specific keywords or phrases. 
• Keyword matching: Using simple algorithms to scan for specific words or phrases in 
user input and respond based on the presence of these keywords. 
• Machine Learning Models: Applying simpler machine learning models like decision 
trees or nearest neighbors that do not require the complex data preprocessing 
typical in NLP. 
• Develop a graphical user interface (GUI) for real-time interaction with users. The GUI should 
be designed to facilitate easy communication between the user and the chatbot, regardless 
of the underlying technology. 

**Expected Outcome**: A functional Python chatbot capable of recognizing and responding to user 
queries through pattern matching, rule-based responses, or simpler machine learning algorithms. 
While it may not understand language with the depth of NLP-based systems, it should effectively 
address user needs within its designed scope, thereby improving the efficiency of customer service 
operations. 

**Additional Requirements and Considerations**:

• **Transparency**: Clearly communicate the limitations of the chatbot to users, especially in 
terms of understanding complex queries or providing contextually relevant responses. 

• **Scalability**: Design the system with scalability in mind, allowing for the addition of more 
complex algorithms or a transition to NLP methods in the future. 

• **User Experience**: Ensure the chatbot provides a positive user experience, with clear 
responses and guidance on how users can phrase their queries for best results.
## Run Locally

Clone the project

```bash
  git clone https://github.com/blackwallpurplestone/acm_project_chatbot
```

Go to the project directory

```bash
  cd acm_project_chatbot
```

Install dependencies in your local system

```bash
  pip install requirements.txt
```


````
Run train_bot.ipynb
Run chat_bot.ipynb
````


