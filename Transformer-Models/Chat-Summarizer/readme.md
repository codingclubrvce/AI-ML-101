# Chat summarizer  📚🗣️

## Overview🌐📝

Welcome to the Google PEGASUS Text Summarization Project ✨🌟 ! This project leverages the power of the PEGASUS : (Pre-training with Extracted Gap-sentences for Abstractive Summarization) model developed by Google. The goal of this project is to provide a robust and user-friendly chat summarization tool that can generate concise and coherent summaries from lengthy chat conversations.

## Table of Contents📜

[Packages](##Packages)

[About the Model](##About-the-model)

[Dataset details](#Dataset-details)

[Usage](#Usage)


## Packages📦

Find it in [requirements.txt](https://github.com/codingclubrvce/AI-ML-101/blob/bcc19e41544c64b466ebedc4966633cdc8747c94/Transformer-Models/Chat-Summarizer/requirements.txt) (Do not worry about all the packages 😅 )
You can refer the code for simpler version

## About-the-model🤖

Google PEGASUS is a state-of-the-art natural language processing model developed by Google Research. PEGASUS stands for Pre-training with Extracted Gap-sentences for Abstractive Summarization. It is designed for abstractive text summarization, a task that involves generating concise and coherent summaries of long pieces of text while preserving the key information.

Check out [Extractive vs Abstractive Summarization](https://www.analyticsvidhya.com/blog/2023/03/exploring-the-extractive-method-of-text-summarization/#:~:text=Extractive%20summarization%20techniques%20select%20and,of%20the%20original%20text%20intact).

Key features and concepts of the PEGASUS model include:

1. **Abstractive Summarization:** PEGASUS belongs to the category of models that perform abstractive summarization, which means it doesn't simply extract sentences from the original text but generates new sentences that capture the essence of the content.

2. **Pre-training with Gap Sentences:** PEGASUS is pre-trained using a denoising autoencoder objective, where sentences are randomly sampled and removed, and the model is trained to reconstruct the original document. This pre-training helps the model learn a rich representation of language.

3. **Gap Sentences Extraction:** PEGASUS introduces a novel gap-sentence generation method, where sentences are randomly selected and masked during pre-training, and the model is tasked with predicting these masked sentences during training.

4. **Fine-tuning for Summarization:** After pre-training, PEGASUS is fine-tuned specifically for abstractive summarization tasks. It is trained on summarization datasets to learn the nuances of generating concise and coherent summaries.

5. **Positional Embeddings:** Similar to other transformer-based models, PEGASUS uses positional embeddings to capture the sequential order of words in a sentence, enabling the model to understand the context and structure of the input text.

6. **Transformer Architecture:** PEGASUS employs the transformer architecture, a powerful neural network architecture known for its effectiveness in processing sequential data. This architecture allows the model to capture long-range dependencies in the input text.

## Advantages of PEGASUS:

1. **Abstractive Summarization** 

2. **State-of-the-Art Performance:** PEGASUS has achieved state-of-the-art performance on various summarization benchmarks, showcasing its effectiveness in generating high-quality summaries across different domains and types of input text.

3. **Versatility:** While initially designed for summarization tasks, the pre-trained PEGASUS model can be fine-tuned for other natural language processing tasks, demonstrating its versatility in understanding and generating human-like text.


## Disadvantages of PEGASUS:

1. **Computational Resources:** Training and fine-tuning large transformer models like PEGASUS require significant computational resources.

2. **Complexity:** The architecture of PEGASUS, like other transformer models, is complex. This complexity might make it challenging to deploy the model in resource-constrained environments or on edge devices.

3. Learn more about the [Pegasus model](https://blog.research.google/2020/06/pegasus-state-of-art-model-for.html)

## Dataset-details

The dataset on which the pegasus is fine tuned upon is the Samsum dataset. The dataset contains conversations between two individuals and a summary of these conversations. This dataset provides a practical use case and one of the few datasets out there which are small enough so that the pegasus can be fine tuned on without crashing a colab notebook.

Dataset link: https://huggingface.co/datasets/samsum

## Usage🚀

It is recommended to run the code on a colab notebook with GPU as runtime accelerator. You will need to have a good GPU (RTX 3050 range) to be able to run it locally.





