# Local Llama 3.2 with Ollama, LangChain & Pydantic

This project demonstrates how to run a local Large Language Model (LLM) using Ollama and interact with it programmatically through LangChain and Pydantic.

The notebook walks through the process of:

* Installing and configuring Ollama
* Downloading and running the Llama 3.2 model locally
* Connecting to the model using LangChain
* Creating structured outputs with Pydantic
* Building reusable AI workflows that can be extended to other Ollama-supported models

## Prerequisites

* Python 3.10+
- Ollama v0.0.0+ installed
* Llama 3.2 model downloaded
* Jupyter Notebook or Jupyter Lab

## Full Tutorial 
Youtube 
https://youtu.be/RrGf6gtkSqE


## Installation

### 1. Install Ollama

Visit the official Ollama website and install the appropriate version for your operating system.

After installation, verify it is working:

```bash
ollama --version
```

### 2. Download Llama 3.2

```bash
ollama pull llama3.2
```

Verify the model is available:

```bash
ollama list
```

### 3. Install Python Dependencies

```bash
pip install langchain
pip install langchain-community
pip install langchain-ollama
pip install pydantic
pip install jupyter
```

Or install everything at once:

```bash
pip install langchain langchain-community langchain-ollama pydantic jupyter
```

## Running the Notebook

Start Jupyter:

```bash
jupyter notebook
```

Open:

```text
LOCAL_Experiment1_ollama_model.ipynb
```

Run the notebook cells sequentially.

## What You'll Learn

### Local LLM Inference

Interact with a locally hosted Llama 3.2 model without relying on external APIs or cloud services.

### LangChain Integration

Use LangChain to:

* Create prompts
* Manage model interactions
* Build reusable AI pipelines
* Chain multiple processing steps together

### Structured Outputs with Pydantic

Generate predictable and validated responses using Pydantic models.

Benefits include:

* Type safety
* Validation
* Consistent output formatting
* Easier integration into applications and automation workflows

## Extending to Other Models

Although this notebook uses Llama 3.2, the same approach works with many Ollama-supported models, including:

* Mistral
* Qwen
* Gemma
* DeepSeek
* Phi
* Codellama

Simply download the desired model:

```bash
ollama pull <model-name>
```

and update the model name in the notebook configuration.

## Example Use Cases

* SOC automation
* Security alert enrichment
* Structured ticket analysis
* Threat intelligence summarisation
* Local AI assistants
* RAG applications
* Research and experimentation
* Offline AI workflows

## Why Run Models Locally?

Running models locally provides:

* Improved privacy
* No API costs
* Reduced data exposure
* Offline operation
* Full control over the AI stack

## References

* Ollama Documentation
* LangChain Documentation
* Pydantic Documentation

## License

This project is intended for educational and experimentation purposes.
