# Extra steps

```sh
kubectl create secret generic hf-token-secret \
  --from-literal=HF_TOKEN=your_actual_token_here
```

## Steps

- Get trtllm-source working
- Get trtlllm-target working
- Test