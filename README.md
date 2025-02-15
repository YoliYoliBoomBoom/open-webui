To run the chat interface, run 
```bash
cd <this_workspace>
docker compose up
```

if you don't have ollama downloaded in local, add http://ollama:11434 from Admin Panel-Settings-Connections; otherwise models from ollama will be detected by default.

To add external models such as Azure OpenAI models, upload the pipeline.py, to add several models from the same external api, upload another pipeline.py with different file names.
Also add a .env file with the following env variables:
AZURE_OPENAI_ENDPOINT='you azure openai endpoint'
AZURE_OPENAI_API_KEY='your azure openai api key'
AZURE_OPENAI_API_VERSION='your azure openai api version'
AZURE_OPENAI_DEPLOYMENT_NAME='your azure openai deployment name'