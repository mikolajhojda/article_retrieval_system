# Article Retrieval System using Mistral7b, LangChain and ChromaDB
This README provides instructions on how to use an Article Retrieval System implemented with Mistral7b, LangChain and ChromaDB. I built this notebook on the Kaggle platform, as I didn't have enough local resources to use some LLMs. The main reason to choose Kaggle was high-performance computing. I mean free access to powerful GPUs which significantly accelerate LLM computations. Training or running complex LLM tasks locally on my machine might be slow or infeasible due to hardware limitations.

# Content of this repo
* <a href="https://github.com/mikolajhojda/article_retrieval_system/blob/main/model.ipynb">Notebook with the Article Retrieval System</a>
* <a href="https://github.com/mikolajhojda/article_retrieval_system/blob/main/report.md">System design report</a>

# Setup
To run the Article Retrieval System in a Kaggle Notebook you can copy my notebook (<a href="https://www.kaggle.com/code/mikolajhojda/article-retrieval-system-using-mistral7b-and-lan/">link</a>).
If you want to run it locally, I suggest downloading my notebook, data, and Mistral7B locally.

# Data
Dataset is a comprehensive collection of blog posts sourced from Medium, focusing specifically on articles published under the "Towards Data Science" publication (<a href="https://www.kaggle.com/datasets/meruvulikith/1300-towards-datascience-medium-articles-dataset">link</a>).

# Usage
To use the Article Retrieval System:
1. Define a query
```python
query = "What is Word2Vec?"
```
2. Retrieve relevant documents (print 3 documents by default):
```python
search_articles(query)
```
3. Generate an answer to the query
```python
generate_answer(query)
```

# Example
```python
#Define a query
query = "What is Word2Vec?"

#Retrieve relevant documents
search_articles(query)

#Generate an answer
generate_answer(query)
```
# Conclusion
Thank you for exploring the Article Retrieval System using Mistral7b and LangChain! I hope you find it useful. If you have any questions or suggestions, feel free to reach out.
