# Chat

Chat is an innovative feature that allows users to interact with an AI-powered assistant within the context of a selected Zora profile. This feature enhances the user experience by providing personalized and context-aware responses.

## How it Works

1. **Select a Zora Profile**: Choose a Zora profile to provide context for the conversation.
2. **Enter Your Intention**: Type in your question or topic of interest.
3. **Context Addition**: The system automatically adds relevant context using the Myco API.
4. **AI-Powered Response**: OpenAI's API is used to generate and stream a contextually appropriate response.

## API Endpoint

The Chat feature utilizes the following Myco API endpoint to gather context:
`GET /api/chat/context?address={selected_profile_address}`

This endpoint fetches the context for the selected Zora profile, which includes the user's Zora Score, the list of tokens they have created, and other relevant information.

## Benefits

- **Personalized Interactions**: Get responses tailored to the context of a specific Zora profile.
- **Enhanced Understanding**: The AI assistant can provide more accurate and relevant information by considering the profile's context.
- **Streamlined Communication**: Easily obtain information about a creator's work, collections, or general blockchain topics.

## Use Cases

- Inquire about a creator's recent works or collections
- Get explanations about blockchain concepts in the context of a specific profile
- Discover insights about a creator's style or themes

## Demo

Watch this short video to see Chat in action:

{% embed url="https://www.youtube.com/watch?v=your_demo_video_id" %}

## Future Developments

As we continue to improve the Chat feature, we plan to:

- Expand the context sources to provide even more comprehensive responses
- Implement user feedback mechanisms to refine the AI's understanding and responses
- Introduce multi-lingual support for global accessibility

For the latest updates and feature releases, keep an eye on our official channels and documentation.

```

```
