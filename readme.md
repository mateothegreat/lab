# lab

## Ollama

Install Ollama only:

```bash
curl -s https://raw.githubusercontent.com/mateothegreat/lab/refs/heads/main/bin/ollama-e2e | bash
```

Install Ollama and pull a model:

```bash
curl -s https://raw.githubusercontent.com/mateothegreat/lab/refs/heads/main/bin/ollama-e2e | bash mistral
```

Run a model with verbose output:

```bash
curl -s https://raw.githubusercontent.com/mateothegreat/lab/refs/heads/main/bin/ollama-e2e | bash mistral "What is the capital of France?"
```
