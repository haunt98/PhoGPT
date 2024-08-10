# ollama

See:

- https://github.com/ollama/ollama/blob/main/docs/modelfile.md
- https://github.com/ollama/ollama/blob/main/docs/import.md

Build:

```sh
ollama create -f ./ollama/Modelfile_Q4_K_M mantis_lego696/phogpt

ollama create -f ./ollama/Modelfile_Q4_K_M mantis_lego696/phogpt_q4_k_m
```

Push:

```sh
ollama push mantis_lego696/phogpt

ollama push mantis_lego696/phogpt_q4_k_m
```

Run:

```sh
ollama run mantis_lego696/phogpt

ollama run mantis_lego696/phogpt_q4_k_m
```
