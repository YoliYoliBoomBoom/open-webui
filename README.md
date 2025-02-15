To run the chat interface, run 
```bash
cd <this_workspace>
docker compose up
```

if you don't have ollama downloaded in local, add http://ollama:11434 from Admin Panel-Settings-Connections; otherwise models from ollama will be detected by default.

To add external models such as Azure OpenAI models, upload the pipeline.py, to add several models from the same external api, upload another pipeline.py with different file names.