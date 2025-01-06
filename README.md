# Final-Project-Chatbot

# **Vet-Pal: A Veterinary ChatBot**

### TAKE NOTE!!
- **The test projects of our chatbot was not uploaded here because it exceeds the file size (25mb) requirements of github. Do not worry though because once you tried the code and run it from top to bottom, then it will automatically make the same test project as long as you use our initial dataset(placed on the Initial Dataset folder).**

## Powerpoint Slideshow
---

https://github.com/user-attachments/assets/918ec709-c28a-4d23-85f1-4fa9a0614df0

## Chatbot Video Presentation
---

https://github.com/user-attachments/assets/6ff99b45-d5fa-46cd-9bf0-4c4cb58db4ac

**!! THE VIDEO WAS COMPRESSED SINCE IT EXCEEDED 10MB SO ITS VIDEO QUALITY WAS POOR. THE VOICES ARE CLEAR HERE, SO IT IS OKAY. CHECK THE FOLDER ABOVE NAMED 'VET-PAL CHATBOT VIDEO PRESENTATION' TO WATCH THE GROUP PRESENTATION OF THE PROJECT !!**

## Introduction
---
The veterinary chatbot was made specifically to provide information about the first aid that pet owners can do at home when they do not know what to do. It can suggest the possible disease a pet has based on symptoms and the home remedies a person can do immediately. The chatbot won’t go beyond what it currently knows though since an actual vet can assess and analyze more serious cases. 

## Domain, reasoning method, Machine Language Algorithm
---
- **Domain** - Our chatbot belongs to healthcare, Pet Healthcare specifically. It’s scope ranges from cats and dogs, which are the common pets we have at home.

- **Reasoning Method** - Our chatbot used a combination of methods. First, we implemented the rule-based reasoning for reliable response. Secondarily with probabilistic reasoning for intent classification and entity extraction.

- **ML Model** - Our Vetpal integrates Rasa’s Natural Language Understanding (NLU) module, which is a technique for intent detection, entity recognition, and pipeline configuration.

  For natural language understanding, We used Rasa’s machine learning pipeline, which used the spaCy for language processing and supervised embeddings for intent classification.

## Dataset
---
Our dataset consists of the following:

**Pet Disease** - All the common diseases that we found among cats and dogs. Both common low and high risks can be found on the dataset.
 
**Description** - Contains the definition of the specific disease.

**Symptoms** - Every possible sign of disease to pets that a pet owner can observe.

**First Aid** - Easy home remedies pet owners can manage to do.

**Products/Medicines** - These are just recommendations from a pet shop. 

## Evaluation

---

We performed different epochs and 100 epochs, the default of the rasa epoch, worked the best for our dataset. We use the rasa command to view the following metrics.

- The accuracy level is 42.9%, meaning that our chatbot struggles with conversational-level challenges  
- The F1-score, Precision, and Accuracy at  85.7%, suggest that it handles the response to the user reliably after it identifies intents

## **How To Use VET-PAL Chatbot**
---

https://github.com/user-attachments/assets/8cf9ac78-ee54-4083-9e0a-b483c238efd8

## Conclusion
---
- Overall, the project met the requirements we first set in our mind as this topic got approved. It performs its purpose as a substitute veterinarian at home that can give you suggested information and first aid to common pet diseases that are not high-risk and can be cured at home. It achieved decent accuracy and precision during the making of it, which makes it a useful tool for its purpose. 

- In terms of its potential improvements, one is its dataset. Even though it is naturally small since our scope is only cats and dogs and their common diseases, we still think that there are more diseases out there that we have not added. Another is the bot’s intelligence; we think that by improving its architecture and having more time to train the bot, it will be very accurate and intelligent. 
