# own_chatbot
Build your own Chatbot with Python

![image](https://user-images.githubusercontent.com/95492893/144715117-ec244a78-55f2-407e-86f8-6bce16739ed8.png)

**In this tutorial, I will show you how to build your very own chatbot using Python. There are broadly two variants of chatbots, Rule-based and Self-learning.**

**A rule-based bot uses some rules on which it is trained, while a self-learning bot uses some machine-learning-based approach to chat.**
**In this tutorial, I will show you how to create a simple and quick chatbot in python using a rule-based approach.**

## Lets Import the libraries

![c1](https://user-images.githubusercontent.com/95492893/144715247-32ce0253-5911-4fee-a96c-9ea92b8e9296.PNG)

**Create the chatbots list of recognizable patterns and it’s a response to those patterns. To do this we will create a variable called pairs.**
![c2](https://user-images.githubusercontent.com/95492893/144715291-a130e2d3-a524-4789-84fd-fc5258f2633c.PNG)
![c3](https://user-images.githubusercontent.com/95492893/144715332-b49d7c80-6dad-41d6-99c8-2ea9cb4b662d.PNG)
![c4](https://user-images.githubusercontent.com/95492893/144715373-12dabf56-7485-469c-bd38-049b7108474e.PNG)
![c5](https://user-images.githubusercontent.com/95492893/144715436-80b6b1b4-c63d-4c55-b8fd-8cc96693f25d.PNG)


Okay, so as we finished the patterns and responses, let’s take a look at something called reflections. Reflections is a dictionary file that contains a set of input values and corresponding output values.

**For example, if the string input was “I am a programmer”, then the output would be “you are a programmer”.**
![c6](https://user-images.githubusercontent.com/95492893/144715490-c7d3d2b4-cbe6-46b3-85df-3c3e28d171ef.PNG)

**We can also create our own reflections dictionary in the same format as reflections above. Below is an example of how to do this:**

![c7](https://user-images.githubusercontent.com/95492893/144715512-813e53c9-2b35-4a0b-b1ce-a3608b3ed216.PNG)

**Now let’s print a default message, and finish our chatbot:**

**#default message at the start of chat
print("Hi, I'm thecleverprogrammer and I like to chat\nPlease type lowercase English language to start a conversation. Type quit to leave ")
#Create Chat Bot
chat = Chat(pairs, reflections)**

## Now, let’s start a conversation

![c8](https://user-images.githubusercontent.com/95492893/144715611-c5442642-f78e-4506-94be-c0dc42b82b76.PNG)







