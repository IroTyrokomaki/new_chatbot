# new_chatbot README

## new_chatbot Domain

The chatbot is designed to serve as an interactive navigation assistant with additional functionalities. The chosen domain revolves around enhancing the user's navigation experience by providing information related to weather, traffic, gas stations, and location. The motivation is to create a versatile chatbot that addresses common user needs during travel and daily activities.

### Intention

The intention behind selecting this domain is to create a more user-friendly and interactive navigation experience. By integrating natural language understanding, the chatbot aims to simplify the process of obtaining essential information during travel, making it more accessible and engaging for users.

## Scenarios

### Happy Path 1

1. User initiates a greeting.
2. User agrees to continue.
3. User requests weather information for their destination.
4. User inquires about current traffic conditions.
5. User says goodbye.

### Happy Path 2

1. User greets the chatbot.
2. User agrees to continue.
3. User requests current location information.
4. User asks for tomorrow morning's weather forecast.
5. User says goodbye.

### Sad Path

1. User greets the chatbot.
2. User agrees to continue.
3. User seeks information on nearby gas stations.
4. User denies the provided information.
5. User denies again.
6. Chatbot apologizes.
7. User says goodbye.

### Bot Challenge

1. User challenges the chatbot's identity.
2. Chatbot responds, confirming its nature as a bot.

## Desired Capabilities

The chatbot is intended to be capable of:

1. Providing accurate and detailed weather updates for specified locations.
2. Offering real-time traffic information, including alternative routes.
3. Assisting users in finding nearby gas stations and providing relevant information.
4. Sharing the user's current location and responding to location-related questions.
5. Engaging in conversations naturally and contextually, handling affirmations, denials, and relevant inquiries.

## Getting Started

To get started with the chatbot, follow these steps:

1. Clone the repository.
2. Install Rasa using 'pip install rasa'.
3. Train the chatbot using 'rasa train' with the provided nlu.yml, stories.yml, and domain.yml, test_stories.yml files.
4. Run the chatbot using 'rasa shell' and start interacting!

Let's go!
