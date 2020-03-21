# CoronsaVirus_voice_bot
This is a project related to the awareness for the current and the serious issue that is caused due to coronavirus. 
So this is a project to aware people to protect themselves from getting in contact with coronavirus.

To know how to build the basic chatbot using rasa you can check this link:

http://innovateyourself.in/building-an-end-to-end-conversational-chat-bot-cum-assistant-with-rasa/

This project is a multilingual voice bot which will help you talk to your bot in the language yo know to spread awareness in any language.

To do that we will first make a simple chatbot that will take the questions of the as an input and to give back the reply accordingly to spread awareness.
Once we are done with the basic chatbot that can reply to our questions then we can procceed to convert it in to the voice bot and during the conversion process we will use a module named translate to translate the text from one language to the other.

Firstly, install the module in the same environment where you have the packages installed for rasa chatbot. To install it go to the terminal and run:

pip install translate

This will install the translate module. Now you can start using it in the Voice_bot.py file to do the conversion process

Here is the basic code to convert the code from one language to the other:

from translate import Translator
translator = Translator(from_lang='en',to_lang='hi')
translation = translator.translate("hello")

This is convert the word hello in english to hindi.

Rest you can download the code from here and further run it.
