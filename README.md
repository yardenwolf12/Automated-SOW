# Welcome to Automated-SOW

## Description

Functioning as a web-tool, AI-based, and data-driven, "AutomatedSOW", aims to act as a blueprint for project teams, ensuring clarity in expectations and contributing to effective project risk management. It incorporates detailed technical and functional specifications, offering a thorough guide across the software product lifecycle, depicting objectives, tasks, timelines, deliverables, and necessary resources. The User inputs the project's fundamental properties and specification into this tool, and the tool generates a thorough Statements of Work (SOW) that provides insights for the project and development team.

Our initial focus was to develop a POC phase which consists the fundamental logic of a funcional agent based on LLm. Leveraging the "Langchain" framework, for developing applications powered by language models, we created a chain-based functionality agent, with the OpenAi's LLm chat model, "SerpAPI", for retrieving search engine results based on promts, and "Faiss", an open source facebook package in python that stores data in embeddings storage.

Based on the POC phase, we developed the algorithm core logic of the agent's methodology, built the server-side rest-API endpoints using "Flask" framework, developed the memory components of the system, including database design, storage mechanisms and server-side integration using "SqlAlchemy", "MySql" for storing the data on AWS RDS database service, and implemented the project's client-side using "React" and "CSS" after designing a mockup using "Figma".
