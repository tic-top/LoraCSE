# 😜LoRACSE: Contrastive Learning of Sentence Embedding using LoRA
##  Final project of EECS 487: Introduction to Natural Language Processing (Umich)
### Autor: Yilin Jia, Sikai Li, Yuqi Mai
### Date: 18 April, 2023

## Instructions

This project involves evaluating the performance of the LoraCSE model through a series of experiments. Here's how to access and run the code:

- Open the LoraCSE.ipynb notebook to view and run the code for all the experiments.
- Follow the instructions provided in the notebook to run the experiments using your GPU and view the results.
- After running the experiments, refer to the accompanying LoRACSE.pdf file for a detailed analysis of the results.

The analysis provided in LoRACSE.pdf offers insights into the performance of the LoraCSE model and its ability to handle different types of data. Use this information to improve the model's accuracy for your specific use case.



## Performance

|              Model              | Avg. STS |
|:-------------------------------|:--------:|
| sup-loracse-bert-base (batch size 512) |  81.55  |
| sup-loracse-roberta-base (batch size 512) |   82.49  |
| sup-loracse-roberta-large (batch size 375) |   84.69  |

## Requirements

To run the experiment, which involves processing large amounts of data with a batch size of 512, your GPU must have at least 40GB of RAM.
Here are the compatible GPUs:

- V100
- A6000
- A40
- RTX3090 (four required)

In this experiment, we use four A40.


## Acknowledgements

We would like to acknowledge the following projects for their contributions to our work:

- [SimCSE](https://github.com/princeton-nlp/SimCSE): Our code has learned a lot from the implementation and ideas presented in this repository.
- [PEFT](https://github.com/huggingface/peft): We have used some of the functionality provided by this library to improve the performance of our code.

We are grateful to the contributors of these projects for sharing their knowledge and expertise with the community.

## Future work
- Learn and use adalora to tune.
- Accelerate the training and evaluation.
- Try to tune debertv3.
- Upload the model to Huggingface.
