To run the chat interface: 
```bash
cd <this_workspace>
docker compose up
```

If you don't have Ollama downloaded locally, add http://ollama:11434 from Admin Panel > Settings > Connections; otherwise, models from Ollama will be detected by default. <br>

To add external models such as Azure OpenAI models:
Upload the pipeline.py file.
To add several models from the same external API, upload another pipeline.py with a different filename.

Also, add a .env file with the following environment variables: <br>
AZURE_OPENAI_ENDPOINT='you azure openai endpoint' <br>
AZURE_OPENAI_API_KEY='your azure openai api key' <br>
AZURE_OPENAI_API_VERSION='your azure openai api version' <br>
AZURE_OPENAI_DEPLOYMENT_NAME='your azure openai deployment name' <br>