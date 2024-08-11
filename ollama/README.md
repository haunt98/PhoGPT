# ollama

See:

- https://github.com/ollama/ollama/blob/main/docs/modelfile.md
- https://github.com/ollama/ollama/blob/main/docs/import.md
- https://huggingface.co/vinai/PhoGPT-4B-Chat-gguf

Build:

```sh
ollama create -f ./ollama/Modelfile mantis_lego696/phogpt
ollama create -f ./ollama/Modelfile_Q4_K_M mantis_lego696/phogpt_q4_k_m
ollama create -f ./ollama/Modelfile_Q8_0 mantis_lego696/phogpt_q8_0
```

Push:

```sh
ollama push mantis_lego696/phogpt
ollama push mantis_lego696/phogpt_q4_k_m
ollama push mantis_lego696/phogpt_q8_0
```

Run:

```sh
ollama run mantis_lego696/phogpt
ollama run mantis_lego696/phogpt_q4_k_m
ollama run mantis_lego696/phogpt_q8_0
```
