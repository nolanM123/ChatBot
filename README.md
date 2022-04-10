# ChatBot

## Description
This is a general-purpose ChatBot about retail clothing and accessories. ChatBot is able to discuss reviews, complaints, product satisfaction, and suggestions. The system has been equipped with a GUI for a cleaner interface and other new systems listed below.

## How to compile and run
- Firstly download the repository.
- Make sure program dependencies are downloaded:
    - pip install nltk
    - pip install spacy
    - python -m spacy download en
    - pip install googletrans
    - pip install googlemaps
- Then run the "Main.py" file.

## Individual Assignment Code Features
### Google Translate API (5 points)
- The google translate api allows the user to ask questions in 108 diffrent languages and get responses in the same language automatically.

**example**

    English
        User: Hello!
        Customer Service: Howdy! I am here for any input on are products you have!

    French
        User: Bonjor!
        Customer Service: Customer Service: Bonjour! En quoi puis-je vous aider?
    
    Spanish
        User: ¡Hola!
        Customer Service: ¡Hola! ¿En qué puedo ayudarte?

### Google Places API
- The google places api allows the bot to suggest places based on what the user is looking for.

**example**

    User: I hate my new bag!
    Customer Service: I am sorry to hear that about your bag's. Have you tried shopping at Bentley's?

    User: I hate the bag I bought!
    Customer Service: I am sorry to hear that about your bag. Have you tried shopping at Hot Topic?
