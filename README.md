# Langchain Conversational Chatbot

This is an example showing you how to enable coherent conversation with OpenAI by the support of Langchain framework.

The key components we are using are as follows:
- ConversationChain
- ConversationBufferMemory
- ConversationSummaryMemory
- ConversationBufferWindowMemory
- ConversationSummaryBufferMemory

There are 3 Python notebooks included in this repository.

## [Langchain_Conversational_Chatbot.ipynb](./Langchain_Conversational_Chatbot.ipynb)

This is a simple example of ConversationBufferMemory usage.
## [Langchain_Conversational_Chatbot_SummaryMemory.ipynb](./Langchain_Conversational_Chatbot_SummaryMemory.ipynb)

This is a simple example of ConversationSummaryMemory usage.

## [Langchain_Conversational_Chatbot_Memory_Types.ipynb](./Langchain_Conversational_Chatbot_Memory_Types.ipynb)

In this notebook, we will run 10 queries with the 4 different types of memory components *ConversationBufferMemory*, *ConversationSummaryMemory*, *ConversationBufferWindowMemory* and *ConversationSummaryBufferMemory* respectively.

Token usage per conversation will be collected in these 4 executions and plotted so that we can have a better understanding on how tokens are consumed differently.

Hope it helps. Feel free to PR if you see any issue. Thanks.