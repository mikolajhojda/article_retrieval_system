# Introduction
I decided build the system based on three main components: Mistral7B, LangChain and ChromaDB.

# Why I chose Mistral7b?
The most important reason for choosing Mistral7b was that it is open-source. This means that I could use it without any obstacles. Another reason was its strong performance. It outperforms similarly sized models in many benchmarks. I also considered choosing other models such as Gemma, which is also open-source, and models such as GPT-3.5 Turbo, for which I needed a paid API, however. There were also many resources on which I could learn how to apply Mistral in practice. This was a significant plus compared to Gemma. I also didn't want to pay for an API in the case of the OpenAI product.

# Why I used ChromaDB?
I used ChromaDB, a vector database, because it integrates well with the retrieval stage of RAG. When you provide a prompt or question, RAG uses ChromaDB to search for relevant passages in your data based on their vector representations. An important functionality in ChromaDB was similarity search. Moreover, ChromaDB is specifically designed to store and manage high-dimensional vectors. In RAG allows for fast retrieval of similar vectors based on the query, making the search process efficient.

# Why I used LangChain?
LangChain has a number of components designed to help build Q&A applications, and RAG applications more generally. LangChain excels at simplifying complex workflows like RAG. It separates tasks like data retrieval, vector encoding, and LLM interaction into manageable modules. This makes it easier to build, understand, and maintain RAG system. It also offers built-in components for interacting with vector databases like ChromaDB.

# Problems that I encountered
One of the biggest problems I encountered was the lack of local resources to work on LLM. An option I considered was using APIs, which, however, come with a fee. So I decided to use Kaggle, where you can use many of the models available on the platform, including Mistral7B.

