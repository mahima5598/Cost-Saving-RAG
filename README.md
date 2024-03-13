# Cost-Saving-RAG

This project is about implementing Cost-Saving strategies to RAG from my article: [Cost-Saving Strategies for Large Language Models(LLMs) - Part 1](https://www.linkedin.com/pulse/cost-reduction-strategies-large-language-modelsllms-mahima-chhagani-7642c/?trackingId=8aTtDQ1kRB%2BgVayei%2FdPaA%3D%3D). The repository uses a project inspired by [Santiago Valdarrama's repository](https://github.com/svpino/youtube-rag) and adds cost saving techniques to it.

The project implemets RAG(Retrieval-Augmented Generation) using Pinecone and OpenAI to answer questions from youtube video. The cost saving strategies used in this project are handling prompts efficiently, prompt compression technique using LLMLingua with LangChain and LLM caching with LangChain. Hope you enjoy implementing it!

## Setup

1. Create a virtual environment and install the required packages:

```bash
$ python3 -m venv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

2. Create a free Pinecone account and get your API key from [here](https://www.pinecone.io/).

3. Create a `.env` file with the following variables:

```bash
OPENAI_API_KEY = [ENTER YOUR OPENAI API KEY HERE]
PINECONE_API_KEY = [ENTER YOUR PINECONE API KEY HERE]
```

## For Better Expeience

1. Read the article and keep it open on side: [Cost-Saving Strategies for Large Language Models(LLMs)...](https://www.linkedin.com/pulse/cost-reduction-strategies-large-language-modelsllms-mahima-chhagani-7642c/?trackingId=8aTtDQ1kRB%2BgVayei%2FdPaA%3D%3D).
2. If new to LLMs watch: [Building a RAG application from scratch using Python, LangChain, and ...](https://www.youtube.com/watch?v=BrsocJb-fAo).
3. Read comments and markdown text to understand the code better.
4. Subscribe to my newsletter for more such knowledge: [ALL ABOUT AI](https://www.linkedin.com/build-relation/newsletter-follow?entityUrn=7165846835213914112).
