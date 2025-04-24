# Emo Pillars
Knowledge Distillation Support for Fine-Grained Context-Aware and Context-Less Emotion Classification

## 🔎 Overview

The Emo Pillars pipeline aims to generate diverse, labelled synthetic data by extracting knowledge from LLMs for fine-grained context-less and context-aware emotion classification.

It was developed to create the [Emo Pillars dataset](https://huggingface.co/datasets/alex-shvets/EmoPillars) of 100K contextual and 300K context-less examples using [Mistral-7B-Instruct-v0.2](https://huggingface.co/mistralai/Mistral-7B-Instruct-v0.2).

The dataset was used to train a [collection of multi-label classifiers](https://huggingface.co/collections/alex-shvets/emopillars-67ec9694541e0bc69d62861f), which identify 28 emotion categories in utterances, optionally in a given situation (context).

For more details, please check our [paper](https://arxiv.org/abs/2504.16856).


## 📝 Citation

If you use this work, please cite our [paper](https://arxiv.org/abs/2504.16856):
```
@misc{shvets2025emopillarsknowledgedistillation,
      title={Emo Pillars: Knowledge Distillation to Support Fine-Grained Context-Aware and Context-Less Emotion Classification}, 
      author={Alexander Shvets},
      year={2025},
      eprint={2504.16856},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2504.16856}
}
```
