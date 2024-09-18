# Welcome to my LLM lab!

This is a repo of my experiments and notes while learning about LLMs. I'm starting with a decent theoretical understanding of neural networks, and hands on experience training large models on distributed systems. I'm very comfortable with data and ML engineering.

# What's done

I've completed:

- Andrej Karpathy's [Neural Networks: Zero to Hero guide](https://youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ&si=WLr50vjq8ordxLttz).
- Thoroughly read [The Annotated Transformers](https://nlp.seas.harvard.edu/annotated-transformer/) paper and run the code side-by-side.

I've read:

- Efficiency:
  - [Flash Attention](https://arxiv.org/abs/2205.14135), [Flash Attention 2](https://arxiv.org/abs/2307.08691), [Flash Attention 3](https://arxiv.org/abs/2407.08608)
  - [Paged Attention](https://arxiv.org/abs/2309.06180)
  - [Online Softmax](https://arxiv.org/abs/1805.02867)
  - [Self-attention Does Not Need O(n2) Memory](https://arxiv.org/abs/2112.05682)
- Synthetic Data
  - [GenAI for Synthetic Data Gen: Methods, Challenges and the Future](https://arxiv.org/abs/2403.04190)
  - [A surver of GenAI for Synthetic Data](https://ieeexplore.ieee.org/abstract/document/10122524)

# What's up next
Here are all the things I'd like to do:

### Implementations:
- Implement FlashAttention myself (in Cuda maybe?)
- Implement FSDP myself (no idea how!?)

### Experiments
- Model efficiency experiments. Try out the following and benchmark performance changes:
  - Speculative decoding
  - Knowledge distillation
  - Quantization
  - Pruning
  - Sparsity low ran compression
  - etc
- Play around with LLAMA models locally

### Readings:
- Depthwise Seperable Convolutions for NMT
- One Model To Learn Them All
- Self-Attention with Relative Position Representations
- GANs
- Stable Diffusion
- KANs
- Explore LLM evaluation
- Explore LLM interpretability
