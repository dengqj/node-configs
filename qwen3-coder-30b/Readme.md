# Qwen3-Coder-30B-A3B-Instruct Node

This configuration sets up a GaiaNet node to run `Qwen3-Coder-30B-A3B-Instruct`, a powerful model from the Qwen3 family specifically fine-tuned for coding tasks and general conversation.

## Step 1: Install GaiaNet node

The GaiaNet node software version should be 0.5.4 or higher.

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

## Step 2: Init with the Qwen3-Coder-30B-A3B-Instruct model

```bash
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen3-coder-30b/config.json
```

## Step 3: Start the node

```bash
gaianet start
```

Now you can use the node as a web-based chatbot or as an OpenAI API drop-in replacement for your development tasks.

## References

* **Official Base Model:** [Qwen/Qwen3-Coder-30B-A3B-Instruct](https://huggingface.co/Qwen/Qwen3-Coder-30B-A3B-Instruct)
* **GGUF Formatted Model:** [Tobivictor/Qwen3-Coder-30B-A3B-Instruct-GGUF](https://huggingface.co/Tobivictor/Qwen3-Coder-30B-A3B-Instruct-GGUF)
* **GaiaNet Node Quick Start Guide:** [https://github.com/GaiaNet-AI/gaianet-node](https://github.com/GaiaNet-AI/gaianet-node)