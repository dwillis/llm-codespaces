# llm-codespaces
A template repository for using the Python llm library in Github's Codespaces. Make a copy of this repository template and open it up in codespaces. It will install llm and the llm-gpt4all libraries. Because codespaces is a sandboxed virtual environment, downloading and running large LLMs locally is not advisable. You can run the Orca Mini 3B LLM, which requires 4GB of RAM, like so:

```bash
llm -m orca-mini-3b-gguf2-q4_0 'What is the capital of France?'
```

You also can use codespaces to run LLMs that are accessed via API, such as OpenAI or Amazon Bedrock.