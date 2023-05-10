# Creating-a-Unified-Query-Framework-over-your-Indexes
## AIM : 
LlamaIndex offers a variety of different query use cases. For simple queries, we may want to use a single index data structure, such as a GPTVectorStoreIndex for semantic search, or GPTListIndex for summarization.For more complex queries, we may want to use a composable graph. But how do we integrate indexes and graphs into our LLM application? Different indexes and graphs may be better suited for different types of queries that you may want to run.

In this guide, we show how you can unify the diverse use cases of different index/graph structures under a single query framework.

## References
  [https://gpt-index.readthedocs.io/en/latest/guides/tutorials/sql_guide.html](https://gpt-index.readthedocs.io/en/latest/guides/tutorials/unified_query.html#)

## Requirement OpenAI key
Open OpenAI website(https://platform.openai.com/account/api-keys) and create key , It will use in code.

## Install some pckages on which our dependency

        pip install openai

        pip install llama-index 
 
## To Run Code 
        Here, I'm using Jupyter Notebook to write code so you can run code to select cell from above to down.
