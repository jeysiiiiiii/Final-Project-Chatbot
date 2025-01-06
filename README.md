# Final-Project-Chatbot

# **Vet-Pal: A Veterinary ChatBot**

## Chatbot Presentation
---
(video)

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

## **How To Use VET-PAL Chatbot**
---
(video)

## Conclusion
---
- Overall, the project met the requirements we first set in our mind as this topic got approved. It performs its purpose as a substitute veterinarian at home that can give you suggested information and first aid to common pet diseases that are not high-risk and can be cured at home. It achieved decent accuracy and precision during the making of it, which makes it a useful tool for its purpose. 

- In terms of its potential improvements, one is its dataset. Even though it is naturally small since our scope is only cats and dogs and their common diseases, we still think that there are more diseases out there that we have not added. Another is the bot’s intelligence; we think that by improving its architecture and having more time to train the bot, it will be very accurate and intelligent. 
