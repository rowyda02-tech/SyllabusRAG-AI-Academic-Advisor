**Abstract**

Navigating academic syllabi can be a complex task for students, often involving the synthesis of frag-
mented information regarding course contents, prerequisites, and administrative rules. This project
is about SyllabusRAG, a Retrieval-Augmented Generation (RAG) system designed to act as an AI
Academic Advisor for the Data Science Master’s degree at the University of Milano-Bicocca. Leverag-
ing a small but capable Large Language Model (Qwen3-4B-Instruct) and a hybrid retrieval strategy
(BGE-M3), the system addresses specific challenges in academic data, such as integrated course
modules. Furthermore, we implement a conversational history module capable of query rewriting to
handle context-dependent follow-up questions. Evaluation against a ground-truth dataset demon-
strates that while standard RAG improves factual retrieval, our history-aware architecture achieves
an 88.1% improvement in accuracy for context-dependent follow-up questions compared to stateless
baselines.
