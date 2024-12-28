![PyPI - Version](https://img.shields.io/badge/Pyhton-v3.11.10-blue)
![PyPI - Version](https://img.shields.io/badge/chromadb-v0.5.23-brown)
![PyPI - Version](https://img.shields.io/badge/llama%20index-v0.12.5-blue)
![PyPI - Version](https://img.shields.io/badge/OpenAI-v1.57.1-%23000055)
![PyPI - Version](https://img.shields.io/badge/OpenAI_model-gpt_3.5_turbo-%23000055)

# Creating_ChromaDBs_sepsis_related
This repository describes how to create sepsis-related vector stores to be used for [Retrieval Augmented Generation](https://arxiv.org/pdf/2312.10997) 
as a tool within the [Multiagent Approach](https://arxiv.org/pdf/2311.10537). 

Created persistent databases are based on the [Chromadb platform](https://www.trychroma.com/). The embedding model is *BAAI/bge-base-en-v1.5* 
with *cosine* embeding function and [llamaIndex](https://docs.llamaindex.ai/en/stable/) is used for orchestration. The inference engine is *gpt-3.5-turbo*.

*Articles_sample_list.txt* contains a sample list of articles that can serve as the core for one of the databases (e.g., concerning sepsis management).

The code is available in *Creating_ChromaDBs_sepsis.ipynb*.
