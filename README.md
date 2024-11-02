# Chatbot-Using-Hugging-Face-and-Streamlit-.ipynb
Chatbot : Using Hugging Face and Streamlit .ipynb

Tech Stack
Hugging Face
Streamlit
Python
Libraries / Dependency required
langchain
llama-index
llama-cpp-python
What is langchain ?
LangChain is a framework for developing applications powered by language models. It enables applications that:

Are context-aware: connect a language model to sources of context (prompt instructions, few shot examples, content to ground its response in, etc.)
Reason: rely on a language model to reason (about how to answer based on provided context, what actions to take, etc.)
Link:- https://python.langchain.com/docs/get_started/introduction

What is llama-index ?
LLMs offer a natural language interface between humans and data. Widely available models come pre-trained on huge amounts of publicly available data like Wikipedia, mailing lists, textbooks, source code and more.

However, while LLMs are trained on a great deal of data, they are not trained on your data, which may private or specific to the problem you’re trying to solve. It’s behind APIs, in SQL databases, or trapped in PDFs and slide decks.

LlamaIndex solves this problem by connecting to these data sources and adding your data to the data LLMs already have. This is often called Retrieval-Augmented Generation (RAG). RAG enables you to use LLMs to query your data, transform it, and generate new insights. You can ask questions about your data, create chatbots, build semi-autonomous agents, and more. To learn more, check out our Use Cases on the left.

Link:- https://docs.llamaindex.ai/en/stable/

What is llama-cpp-python?
llama-cpp-python is a Python binding for llama.cpp.

It supports inference for many LLMs models, which can be accessed on Hugging Face.

Link:- https://python.langchain.com/docs/integrations/llms/llamacpp
