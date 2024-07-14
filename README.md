# Policy-doc-RAG-llamaindex
A RAG system on insurance policy document using llamaindex framework.

We use Llama-index to build a simple RAG based Question-Answering system on an insurance policy document.

Below are the key components of the RAG

- Framework- Llamaindex
- LLMs- GPT 3.5 and Mistral 8x7b
- Embeddings- OpenAI and JinaAI embeddings
- Index & Retriever- Vector Store index and Retriever

The RAG was evaluated using the RAG evaluator pack for `relevancy`, `correctness` and `faithfulness`. Achieved a relevancy and faithfulness score of 1. Correctness is 0.8. 
This can be improved by further fine-tuning on the LLMs, embeddings, chunk size or using advanced retriever techniques.
