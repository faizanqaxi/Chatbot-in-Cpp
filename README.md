CHATBOT

FEATURES:
* It is a file handling based chatbot
* It uses tokenization, stemming, string filtering, hash functions, hash maps etc
* It loads the data files into hashmaps and then uses different techniques to answer the questions based on the data it has in the questionAnswers.txt file
* The exact same questions don't need to be in the data files, the program uses different techniques to understand and map the questions
* You can feed it more Questions and Answers into that file to expand it's knowledge
* If it is unable to answer a question, it will ask the user to tell it the answer so it can answer that question next time when asked.

NOTE:
IF CHATBOT DOES NOT WORK:
 
Copy the lemmatizationData.txt file and questionAnswers.txt files
into some location on your system then change their paths in code in the main function to the path you copied those files in.

After compiling and running the Source file, wait for a minute in the start for this chatbot to load all the data from the files into the datastructures
Once it is loaded, you can chat with the bot
