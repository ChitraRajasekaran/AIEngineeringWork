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