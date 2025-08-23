# A MedGemma 27B node

**Step 1:** Install Gaia node

> The  Gaia node software version should be 0.5.4 or higher. 

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the MedGemma 27B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/medgemma-27b-it/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/collections/google/medgemma-release-680aade845f90bec6a3f60c4)
* [GGUF formatted model](https://huggingface.co/unsloth/medgemma-27b-it-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
