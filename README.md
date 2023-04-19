# LoRACSE: Contrastive Learning of Sentence Embedding using LoRA

### date: 18/4/2013

## Instruction

Everything is done in LoraCSE.ipynb

The LoraCSE.ipynb contains all the experiments.(optimizer with Lion)

The LoraCSE_recorded.ipynb records part of previous experiments.(optimizer with AdamW)

## Performance

|              Model              | Avg. STS |
|:-------------------------------|:--------:|
| sup-loracse-bert-base (batch size 512) |  81.55  |
| sup-loracse-roberta-base (batch size 512) |   82.49  |
| sup-loracse-roberta-large (batch size 375) |   84.69  |

## Requirement

To run the experiment with batch size 512 , the GPU RAM should be at least 40G.

So, you can run on one V100, V6000, V40 or four RTX4090.