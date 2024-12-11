# MoKGNN

## Model Descriptions

We briefly introduce the GNN models and the language models we used in the main text.

**GCN**. Graph Convolutional Network (GCN) is a classical model that works by performing a linear approximation to spectral graph convolutions.

**GraphSAGE**. GraphSAGE is a GNN model that focuses on inductive node classification, but can also be applied for transductive settings.

**RevGAT**. RevGAT combines reversible connectivity with a deep network architecture to form a deep and efficient GNN.

**BERT**. Bidirectional encoder representations from Transformers (BERT) utilizes a transformer architecture that employs self-attention mechanisms to capture word relationships within sentences. This enables the model to effectively consider both the preceding and succeeding contexts of a word, facilitating bidirectional language comprehension. BERT undergoes unsupervised pre-training on an extensive text corpus, where it predicts masked words within sentences and acquires the ability to encode contextual information.

**RoBERTa**. Robustly Optimized BERT (RoBERTa) is a variant of BERT. RoBERTa incorporates additional modifications during pre-training to optimize its performance. In the pre-training phase, it trains on a vast corpus of unlabeled text data by employing masked language modeling while excluding the next sentence prediction task. RoBERTa significantly expands the amount of training data used, enabling the acquisition of more comprehensive and robust language representations.

**LLaMA 2**. LLaMA 2 is a collection of pretrained and fine-tuned generative text models ranging in scale from 7 billion to 70 billion parameters. The tuned version use supervised fine-tuning and reinforcement learning with human feedback to align to human preferences for helpfulness and safety.

**Mistral**.  Mistral 7B is an open source large model released by the Mistral AI team, which outperforms LLaMA 2 13B on many benchmarks.


We will release our code soon.
