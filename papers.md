## 🤖 GenerativeAI

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762): Query, Key, and Value are all you need* (*Also position embeddings, multiple heads, feed-forward layers, skip-connections, etc.)
- [GPT: Improving Language Understanding by Generative Pre-Training](https://cdn.openai.com/research-covers/language-unsupervised/language_understanding_paper.pdf): Decoder is all you need* (*Also, pre-training + finetuning)
- [BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding](https://arxiv.org/abs/1810.04805): Encoder is all you need*. Left-to-right language modeling is NOT all you need. (*Also, pre-training + finetuning)
- [GPT3: Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165): Unsupervised pre-training + a few* examples is all you need. (*From 5 examples, in Conversational QA, to 50 examples in Winogrande, PhysicalQA, and TriviaQA) 
- [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361): Larger models trained on lesser data* are what you you need. (*10x more compute should be spent on 5.5x larger model and 1.8x more tokens)
- [Chinchilla: Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556): Smaller models trained on more data* are what you need. (*10x more compute should be spent on 3.2x larger model and 3.2x more tokens)
- [LLaMA: Open and Efficient Foundation Language Models:](https://arxiv.org/abs/2302.13971) Smoler models trained longer—on public data—is all you need
- [InstructGPT: Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155): 40 labelers are all you need* (*Plus supervised fine-tuning, reward modeling, and PPO)
- [LoRA](https://arxiv.org/abs/2106.09685): Low-Rank Adaptation of Large Language Models: One rank is all you need
- [RAG: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401): Semi-parametric models* are all you need (*Dense vector retrieval as non-parametric component; pre-trained LLM as parametric component)
- [Whisper](https://arxiv.org/abs/2212.04356): Robust Speech Recognition via Large-Scale Weak Supervision: 680k hrs of audio and multitask formulated as a sequence is all you need.
