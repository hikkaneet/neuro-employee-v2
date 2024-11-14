# neuro-employee-v2
Neuro-employee in Jupyter Notebook

# Description
In this notebook, I defined the "profession" of a neuro-employee, their "inner world," and key "instructions" they must follow to implement a system prompt for them. I developed a knowledge base structure for the neuro-employee, paying particular attention to the quality and composition of the data. I chose between LlamaIndex and LangChain frameworks for implementing the neuro-employee, trying to use a Russian-language contour LLM. I traced the work of the neuro-employee, identifying their weaknesses and potential hallucinations. Upon detecting hallucinations, I took measures to eliminate them and anticipated potential risks of hallucinations in the RAG system, applying appropriate techniques from the lessons. I implemented several methods to improve RAG, considering that neuro-employees are already well-known thanks to articles on Habr, and aimed to offer a solution that stands out among others. I also addressed the security aspects of the neuro-employee, adding at least basic query filtering.

# Input Data:
The neuro-employee acts as an online manager-consultant.
The knowledge base is a graph store, with information extracted from docx documents.
The LlamaIndex framework.
The saiga_mistral_7b model.
The arize phoenix tracer.

# Tasks of the Neuro-Employee:
Refer to the database to obtain information.
Answer accurately, based only on data from the source.
If information is unavailable, honestly say that the answer is unknown.
Avoid excessive emotions, phrases, and guesses.
Understand key customer queries and check them against the graph base.

# Data:
For the example, 3 docx documents with a clear structure of headings h1 - h2 - h3 are used.

You can see the notebook with output cells on Google Colab at the link:
https://colab.research.google.com/drive/1tw6ZsagzOJf_Ft24SmLIi59Hg1PgUS5j?usp=sharing
