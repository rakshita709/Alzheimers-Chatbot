# Alzheimers-Chatbot

Chatbot for Alzheimer's patients:
- Helps patient boost their memory by playing games like identifying people/locations from picture
- Rewards them for completion
- Provides positive feedback assurance
- Enables patient to add information about any person like friends and acquaintances
- Allows interaction via text
- Provides suggestions in order to minimise the texting for user

Building blocks of Chatbot:
- DialogFlow agent: The conversation system which understands the semantic meaning of input from user. 
- The main components of agent: Intents, Entities, Parameters
- Fulfillment (webhook): The code that contains logic to handle requests and also used to pull data from database
- Firestore Database: Stores the relevant information about user like people/locations
- Kommunicate: The plugin which has been used to integrate the chatbot with the application

# Screenshot from the chatbot:
- We can add people's names in the chat bot and their images, as part of brain excercise for the patient, to help them remember their loved ones.

    ![Chatbot SS](https://user-images.githubusercontent.com/36971218/126081847-37153344-74e1-4b82-a666-cc391c0c4c6c.jpeg)
