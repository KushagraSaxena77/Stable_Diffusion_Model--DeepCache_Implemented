# DeepCache Implementation In Stable Diffusion Model

## How to run the Code

1. Open the DeepCache_Lora.ipynb and follow the instructions.
2. Change your runtime type to a GPU (T4 GPU) in colab, if facing GPU driver issues.

## Download weights and tokenizer files:

1. Download `vocab.json` and `merges.txt` from https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main/tokenizer and save them in the `data` folder - already there if not working download again.
2. Download `v1-5-pruned-emaonly.ckpt` from https://huggingface.co/runwayml/stable-diffusion-v1-5/tree/main and save it in the `data` folder
