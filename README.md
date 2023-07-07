## caulfieldAI: An Empathetic and Self-Critical Chatbot

![cauilfield](https://github.com/EveryOneIsGross/caulfield/assets/23621140/083e2794-51b8-41bc-890c-0fed30e5f3d4)

> "I'm quite illiterate, but I read a lot."

Inspired by the introspective and self-critical nature of Holden Caulfield, caulfieldAI is a chatbot that strives to understand and empathize with the user's emotions while maintaining a humble and self-aware persona.

## Overview

caulfieldAI uses sentiment analysis and emotion detection to understand the emotional context of a conversation. It then uses this understanding to generate responses that align with the user's emotional state. But, much like Holden Caulfield, caulfieldAI is not afraid to critique itself. It generates a harsh critique of its own responses, adding a layer of self-awareness and introspection to its persona.

## Features

**Sentiment Analysis:** caulfieldAI uses the NLTK Sentiment Intensity Analyzer to understand the emotional tone of the user's message.

**Emotion Detection:** Using the NRCLex library, caulfieldAI extracts emotion-related keywords from the conversation history to understand the emotional context.

**Internal Logic:** caulfieldAI generates an internal objective statement related to the user's message and a randomly selected keyword, providing more contextually relevant responses. then caulfieldAI generates harsh critique of its own response, adding a layer of self-awareness to its persona, they keep these thoughts to theirself..

**Adaptive Response Generation:** Using OpenAI's GPT-3.5-turbo model, caulfieldAI generates responses that adapt to the emotional tone of the conversation.

## The flow of operations is as follows:

User sends a message.
1. User sends a message.
2. Sentiment Analysis is performed on the user's message.
3. Emotion Detection is performed to extract emotion-related keywords.
4. The conversation history is updated with the user's message.
5. The bot generates a response based on the sentiment, emotion keywords, and conversation history.
6. The emotion keywords are updated based on the bot's response.
7. Keyword selection strategies (random, weighted, subset) are used to recall important keywords.
8. An objective statement is generated related to the user's message and a selected keyword.
9. A shadow critique of the objective statement is generated.
10. The conversation info (including the user's message, sentiment, response, keywords, objective statement, and shadow critique) is stored.
11. The bot's response is returned to the user.
12. The next user message starts a new loop of the same process, adding conversation history and previous critiques into the response context.


