# HealthCare-ChatBot
HealthCare ChatBot is used to diagnose the disease by entering symptoms and answering few related questions to it using Infermedica API.

**Package required to install:** None

As we are using libraries like tkinter(for building GUI) and requests(for calling API) that are downloaded in many system when we download python. If above libraries are not present in your system then below given code will help to download this modules.

**For requests module** -> pip install requests



**Which file we needs to run?**

File name : **gui.py** needs to be run to run whole project.

For command prompt : python gui.py

While project contains 3 files:

•	**gui.py** [It contains whole GUI related code]

•	**conversations.py** [It contains conversation between user and bot]

•	**apiaccess.py** [It contains code to access infermedica API]

Features of this project
In GUI format we have added 3 menu like:
1.	File
File contains attributes like: Clear Chat and Exit

2.	Options
In Options we have added Font and Color Theme. Font contains some fonts that are display when you chat with bot. And Color theme changes theme of gui for conversation.

3.	Help
It includes basic information about our project.

What input should be given to run code smoothly?
For starting the program you must write following words as keywords for greetings:
"hello", "hi", "hiii", "hii", "hiiii", "hiiii", "greetings", "sup", "what's up", "hey"
Eg. Hello chatbot
Let’s come to point and use following keywords to chat for healthcare advice: 
"not well", "not feeling well", "ill", "symptoms", "Symptom"
Eg. I am ill right now
As soon as you write above keywords program will ask you for your age, gender and your symptoms. You have to write all your symptoms without pressing enter key.
Eg. I have fever last night and coughing continously. Also having headache like hammering in my head.
After this you will view message from bot of noting your symptoms and you have to press enter to continue further conversations.
Now bot will ask you some questions in which you have to answer them as yes or no. If you write anything else of yes and no it will consider as user don’t know its answer.
At last your report will be generated.
Also if you type keywords like:
“thanks”, “thank you”, “who are you?”, “your name?”, "can you describe your self?", “bye”, “good bye”, “byy”
Bot will reply you with his message.


