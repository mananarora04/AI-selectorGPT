We identified the need for a domain-aware AI assistant capable of selecting appropriate AI
tools in legal, medical, academic, music and finance fields, leveraging Retrieval-Augmented
Generation (RAG) with advanced open-source LLMs. The objectives were:
● Understand and implement RAG pipelines for domain-specific QA.
● Use state-of-the-art language models (e.g., Phi-3 Mini, NVIDIA API, or similar) for answer
generation.
● Build a user-friendly web interface for interaction and testing.

A detailed proposal was submitted outlining the problem, objectives, tools (Python, Hugging
Face Transformers, Streamlit, Chroma), and expected outcomes.

Execution and Demonstration:
The system was implemented with the following features:
● Developed a Streamlit-based web interface for user interaction.
● Indexed domain-specific .txt documents (legal, medical, academic, music and finance)
using Chroma vector database.
● Integrated a free, open-access LLM (e.g., Phi-3 Mini) for answer generation, with optional
support for NVIDIA API endpoints.
● Implemented domain classification to route queries and ensure relevant context retrieval.
● Demonstrated end-to-end question answering, including citation of source documents.
● Documented code and provided sample data files for each domain.
