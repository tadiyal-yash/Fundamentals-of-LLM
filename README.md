# Fundamentals-of-LLM

In this example, we'll work on building an AI chatbot from start-to-finish. We will be using LangChain, OpenAI, and Pinecone vector DB, to build a chatbot capable of learning from the external world using **R**etrieval **A**ugmented **G**eneration (RAG).

We will be using a dataset sourced from the Llama 2 ArXiv paper and other related papers to help our chatbot answer questions about the latest and greatest in the world of GenAI.

By the end of the example we'll have a functioning chatbot and RAG pipeline that can hold a conversation and provide informative responses based on a knowledge base.

### Before you begin

You'll need to get an [OpenAI API key](https://platform.openai.com/account/api-keys) and [Pinecone API key](https://app.pinecone.io).

Rerankers have been a common component of retrieval pipelines for many years. They allow us to add a final "reranking" step to our retrieval pipelines — like with **R**etrieval **A**ugmented **G**eneration (RAG) — that can be used to dramatically optimize our retrieval pipelines and improve their accuracy.

In the example notebook we'll learn how to create retrieval pipelines with reranking using [Pinecone Inference](https://docs.pinecone.io/guides/inference/understanding-inference).
