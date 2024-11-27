# Example Weaviate Agent

In this repository, we create 2 RAG pipelines which in turn become tools for an agent.

1. Weaviate Docs tool
2. Weaviate GitHub issues tool

To run the examples:

```
pip install -r requirements.txt
```
Create a `.env` file and add the API Keys:
```
WEAVIATE_DOCS_URL=URL for Client 1
WEAVIATE_API_KEY=API key for Client 1
WEAVIATE_ISSUES_URL=URL for Client 2
WEAVIATE_ISSUES_KEY=API key for Client 1
OPENAI_APIKEY=Your OpanAI API key
```