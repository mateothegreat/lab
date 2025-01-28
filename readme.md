# lab

## Ollama

Download the script and run with the following (optional) arguments:

| #   | Arguments | Description                     |
| --- | --------- | ------------------------------- |
| 0   | `model`   | Install Ollama only             |
| 1   | `prompt`  | Run a model with verbose output |

Examples:

Run a model with verbose output:

```bash
bash <(curl -s https://raw.githubusercontent.com/mateothegreat/lab/main/bin/ollama-e2e) mistral "What is the capital of France?"
```

Install Ollama and pull a model:

```bash
bash <(curl -s https://raw.githubusercontent.com/mateothegreat/lab/main/bin/ollama-e2e) mistral
```

Install Ollama only:

```bash
bash <(curl -s https://raw.githubusercontent.com/mateothegreat/lab/main/bin/ollama-e2e)
```
