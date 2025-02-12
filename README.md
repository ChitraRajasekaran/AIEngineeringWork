All AI engineering work will be stored in this repo.

Happy Coding!

1) Prompt Engineering
 - Tested user,system and assistant prompting types. 
 - Tested Few shot prompts and chain of thought prompts.
 - Tested Evals : LLM as judge in particular.

2) First RAG Application
 - Import necessary documents and utilities
 - Build vector database to store your vector representations
    How did we do the above two steps? - 
     (We load source documents, We split those source documents into smaller chunks (documents),We send each of those documents to the text-embedding-3-small OpenAI API endpoint,We store each of the text representations with the vector representations as keys/values in a dictionary)
 - RAG -> Dense vector retrieval + In-context Learning
 - Enhancing RAG application to work with PDF files.

3) Langchain powered RAG
  - Focus is on learning how to navigate and build useful applications using LangChain, specifically LCEL, and how to integrate different APIs together into a coherent RAG application!

4) Building Agents with Langchain
  - LangGraph - Building Cyclic Applications with LangChain - Equip our agent with toolbelt to help answer questions and add external knowledge
  - Langsmith evaluator - To do more preprocessing with Langsmith and wrap our LangGraph agent in a simple chain 
  - LangGraph for the "Patterns" of GenAI
        - Prompt Engineering
        - RAG
        - Fine-tuning
        - Agents
5) Building MultiAgent RAG
    - Simple LCEL RAG
    - Helper Functions for Agent Graphs
    - Research Team - A LangGraph for Researching A Specific Topic
    - Document Writing Team - A LangGraph for Writing, Editing, and Planning 
    - Meta-Supervisor and Full Graph

6) Synthetic Data Generation
        - Use RAGAS to Generate Synthetic Data
        - Load them into a LangSmith Dataset
        - Evaluate our RAG chain against the synthetic test data
        - Make changes to our pipeline
        - Evaluate the modified pipeline