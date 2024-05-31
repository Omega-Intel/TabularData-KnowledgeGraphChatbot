# Tabular Data Knowledge Graph Chatbot with RAG and LLM

A cutting-edge chatbot project that leverages the power of knowledge graphs, GPT-3.5, Langchain graph agents, and the Neo4j graph database. It enables users to interact with tabular data (CSV, XLSX, etc.) through natural language queries, facilitating both question-answering (Q&A) and retrieval-augmented generation (RAG) capabilities. Additionally, this project showcases an innovative approach to constructing knowledge graphs from unstructured data by harnessing the capabilities of large language models (LLMs).

## Key Features

- **Natural Language Interaction:** Engage in seamless conversations with a chatbot powered by a knowledge graph derived from tabular data sources.
- **Retrieval-Augmented Generation (RAG):** Leverage the knowledge graph to enhance the chatbot's responses with relevant information from the tabular data.
- **Knowledge Graph Construction:** Demonstrate an advanced technique for building knowledge graphs from unstructured data using state-of-the-art language models.

## Important Notes

- **Database Access Restrictions:** To ensure data integrity and security, it is crucial to limit the Neo4j database connection privileges to READ-only access. Granting WRITE privileges could potentially allow users to manipulate the data through the chatbot interface, posing a significant risk.
- **Knowledge Graph Construction:** Knowledge graphs, which form the backbone of the chatbot's data structure, can be constructed either with input from domain experts or through advanced language models like the Langchain 'LLM Graph Transformer'. The latter approach introduces non-determinism, potentially resulting in slightly different knowledge graph representations with each execution.
- **Query Language Proficiency:** Familiarity with database query languages such as Pandas for Python, SQL, and Cypher can enhance the user's ability to formulate more sophisticated questions and engage in richer interactions with the graph agent.

## Underlying Techniques

The Tabular Data Knowledge Graph Chatbot with RAG and LLM project employs the following key techniques:

1. **Knowledge Graph Construction:** Leveraging advanced language models to build knowledge graphs from unstructured data sources.
2. **LLM Chains and Agents:** Utilizing Langchain's LLM chains and agents to facilitate natural language interactions with the knowledge graph.
3. **Cypher Query:** Querying the Neo4j graph database using the Cypher query language to retrieve relevant information for the chatbot's responses.

## Potential Use Cases

This project has numerous potential applications across various domains, including:

- **Data Exploration and Analysis:** Enabling users to explore and analyze tabular data through natural language queries, facilitating data-driven decision-making.
- **Knowledge Management:** Building knowledge graphs from unstructured data sources to create a centralized repository of structured knowledge.
- **Question-Answering Systems:** Developing intelligent question-answering systems that can provide accurate and relevant responses based on the knowledge graph.
- **Conversational AI:** Enhancing conversational AI agents with the ability to leverage structured knowledge from tabular data sources.

By combining the power of knowledge graphs, large language models, and graph databases, the Tabular Data Knowledge Graph Chatbot with RAG and LLM project offers a cutting-edge solution for natural language interaction with tabular data, opening up new possibilities for data exploration, knowledge management, and conversational AI applications.
