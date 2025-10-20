# A Strand-Rust-Coder-14B Node for Expert-Level Rust Development

This configuration sets up a GaiaNet node using the powerful `Strand-Rust-Coder-14B-v1` model, which is highly specialized for Rust programming tasks.

**Step 1:** Install GaiaNet node

```bash
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the Strand-Rust-Coder 14B model and Rust knowledge base

This command will download the model and configuration directly from your GitHub repository.

```bash
gaianet init --config https://raw.githubusercontent.com/dengqj/node-configs/main/strand-rust-coder-14b/config.json
```

**Step 3:** Start the node

```bash
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.
