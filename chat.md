# Chat

Chat is an innovative feature that allows users to interact with an AI-powered assistant within the context of a selected Zora profile. This feature enhances the user experience by providing personalized and context-aware responses.

## Getting Started

To start using the Chat, visit [https://chat.myco.wtf](https://chat.myco.wtf).

## How it Works

1. **Select a Zora Profile**: Choose a Zora profile to provide context for the conversation.
2. **Enter Your Intention**: Type in your question or topic of interest.
3. **Context Addition**: The system automatically adds relevant context using the Myco API.
4. **AI-Powered Response**: OpenAI's API is used to generate and stream a contextually appropriate response.

## Example Intents

1. How many tokens has this artist created in the past week?
2. How many different chains has this artist released on?
3. What is their Zora score?
4. Can you summarize this artist's recent activity on Zora?
5. What is the most popular collection created by this artist?
6. How does this artist's Zora score compare to the average?
7. What themes or styles are prevalent in this artist's work?
8. Has this artist collaborated with any other notable creators?
9. What was the highest-grossing piece by this artist, and when was it sold?
10. Can you provide insights on this artist's engagement with their community?

## Benefits

- **Personalized Interactions**: Get responses tailored to the context of a specific Zora profile.
- **Enhanced Understanding**: The AI assistant can provide more accurate and relevant information by considering the profile's context.
- **Streamlined Communication**: Easily obtain information about a creator's work, collections, or general blockchain topics.

## API Endpoint

The Chat feature utilizes the following Myco API endpoint to gather context:
`GET /api/chat/context?address={selected_profile_address}`

This endpoint fetches the context for the selected Zora profile, which includes the user's Zora Score, the list of tokens they have created, and other relevant information.
