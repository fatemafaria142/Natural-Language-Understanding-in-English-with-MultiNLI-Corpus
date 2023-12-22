# ConTRoL: ConTextual Reasoning over Long Texts for Natural Language Inference

## Overview
This repository contains code for Natural Language Inference (NLI) leveraging DistilBERT and mBERT models on the ConTRoL dataset. ConTRoL is a novel passage-level NLI dataset specifically designed to test complex contextual reasoning, including logical reasoning, over long texts. It comprises 8,325 "context-hypothesis" pairs meticulously crafted from a competitive selection and recruitment test for police recruitment, exhibiting expert-level quality and challenging reasoning types.

## Dataset
- **ConTRoL Dataset**: The ConTRoL dataset (available [here](https://github.com/csitfun/ConTRoL-dataset)) comprises 8,325 expert-designed "context-hypothesis" pairs, meticulously crafted from police recruitment tests, offering a challenging set of reasoning types for NLI tasks.

## Models
- **DistilBERT and mBERT**: Utilizing these transformer-based models provided by Hugging Face Transformers library,I explore their effectiveness in handling passage-level NLI tasks on the ConTRoL dataset. 

## Usage
To replicate this experiments or use the code:
1. Clone this repository.
2. Install the necessary dependencies specified in `requirements.txt`.
3. Utilize the provided scripts and notebooks to train, fine-tune, or evaluate DistilBERT and mBERT models on the ConTRoL dataset.

