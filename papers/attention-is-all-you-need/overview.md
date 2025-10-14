# Attention Is All You Need

**Authors:**		Ashish Vaswani, Noam Shazeer, Niki Parmar, Jakob Uszkoreit, Llion Jones, Aidan N. Gomez, Łukasz Kaiser, Illia Polosukhin
**Year:**		2017
**Institution:**	Google Brain, Google Research, University of Toronto
**Link:** 		https://arxiv.org/pdf/1706.03762 

## Summary
This is THE paper that proposed the architecture that has revolutionized the field of Generative AI as we know today. The Transformer's breakthrough was showing that attention mechanisms alone could achieve superior performance while being dramatically faster to train. This architectural shift unlocked the ability to train on massive datasets with hundreds of billions of tokens, leading directly to the GPT series, BERT, and every modern LLM including ChatGPT and Claude.
We're doing a deep dive into this paper to understand the key concepts and how this architecture elegantly solved the fundamental limitations of RNNs and LSTMs—particularly the vanishing gradient problem and sequential processing bottleneck—making it possible to train large language models with millions and now trillions of parameters. The parallel processing capability and ability to capture long-range dependencies transformed what was computationally feasible, setting the foundation for the generative AI revolution. Beyond language, the Transformer architecture has proven remarkably adaptable, becoming the backbone of multi-modal models that seamlessly integrate text, images, audio, and video, enabling the next generation of AI systems.

## Key Contributions
- Pure Self-Attention Architecture - Eliminates recurrent (RNN/LSTM) and convolutional layers entirely, demonstrating that self-attention mechanisms alone are sufficient for state-of-the-art sequence modeling
- Multi-Head Attention - Runs multiple self-attention mechanisms in parallel to capture nuanced relationships and disambiguate words by understanding them from different perspectives
- Efficient Attention Mechanism - Introduces an efficient formulation of attention that makes it computationally practical to use self-attention as the sole mechanism for processing large sequences
- Positional Encoding - Injects sequence order information into the model, which is essential for understanding sentence structure since the architecture has no inherent notion of word order
- Parallelizable Architecture - Eliminates sequential computation dependencies, enabling significantly faster training compared to recurrent models

## Key Concepts
- Word Embeddings - Converting tokens to dense vector representations that capture semantic meaning
- Positional Encoding - Adds position information to embeddings so the model understands word order in the sequence
- Self-Attention - Mechanism that allows each word to attend to all other words in the sequence to understand long range context
- Parallel Processing - All positions in the sequence are processed simultaneously rather than sequentially
- Query, Key, Value vectors - Three different projections of each word embedding used to compute attention scores and determine which words to focus on
- Encoder-Decoder Structure - Stacked layers with residual connections and layer normalization that transform input sequences to output sequences
- Attention Masking - Prevents the decoder from "cheating" by looking at future words during training

## Why It Matters
Transformer architecture is now used at the core of 

## My Understanding
[Your thoughts, questions, connections to other papers]

## Implementation Notes
[If you tried to implement anything, or found good implementations]

## Questions/Follow-ups
- [Things you want to explore further]
- [Unclear points to discuss with study group]
