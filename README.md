## Modelfile for Qwen3:14b for Coding

Inspired by this X post:

https://x.com/ivanfioravanti/status/1916934241281061156

I based my adjustments on the post above and the original modelfile:

```
ollama show qwen3:14b > qwen3-dev.modelfile
```

Now we can just run:

```
ollama create qwen3-dev -f qwen3-dev.modelfile
ollama run qwen3-dev # or just run from Aider
```
