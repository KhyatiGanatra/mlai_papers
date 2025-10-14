# 🧠 Transformer Architecture Notes

These notes summarize some of the most **useful references and materials** I’ve shared during our paper review sessions on the *Transformer* architecture.  
They’re meant as a **living document** — part study guide, part annotated reference list — combining both theoretical and practical resources that I personally find valuable when explaining or revisiting transformers.
---

## 🎧 Podcast

**[SuperDataScience — Technical Intro to Transformers and LLMs (Ep. 747, with Kirill Eremenko)](https://www.superdatascience.com/podcast/sds-747-technical-intro-to-transformers-and-llms-with-kirill-eremenko)**  
> *One of my personal favorites.*  
Kirill walks through the **transformer architecture** step-by-step, including the now-famous *“fire story”* analogy (the same one I referenced in our discussion).  
If you prefer a narrative and conceptual flow before diving into code, this episode nails it.

---

## 📺 YouTube

**[Transformers Explained Visually](https://www.youtube.com/watch?v=eMlx5fFNoYc&t=217s)**  
A **super intuitive visual breakdown** of the transformer architecture.  
This is one of those videos I keep revisiting — it helps solidify what’s happening at every step of the attention mechanism and how data flows through the layers.  
Perfect if you like mental models over equations.

---

## 🧩 Interactive Tool

**[Transformer Explainer — by PoloClub](https://poloclub.github.io/transformer-explainer/)**  
A **visual and interactive web app** that lets you explore how each component behaves: multi-head attention, residual connections, layer normalization, etc.  
Extremely useful to *see* what’s going on internally.

---

## 📘 Articles

**[The Illustrated Transformer — by Jay Alammar](https://jalammar.github.io/illustrated-transformer/)**  
Still one of the best conceptual resources available.  
Jay’s post connects the math, the structure, and the intuition beautifully.  
Some of the screenshots I used in my notes come from here (annotated based on our own discussions).

---

## 📄 Papers

**[Attention Is All You Need — Vaswani et al., 2017](https://arxiv.org/pdf/1706.03762)**  
The foundational paper.  
Even after years of model evolution (BERT, GPT, ViT, etc.), it’s still *the* place to start if you want to understand **attention as a core mechanism for sequence modeling**.

---

## 🛠️ Build It From Scratch

Here are a few implementation-oriented references to bridge theory and code:

- **[Build Your Own Transformer From Scratch Using PyTorch](https://medium.com/data-science/build-your-own-transformer-from-scratch-using-pytorch-84c850470dcb)**  
  A hands-on tutorial walking you through building the transformer from the ground up (embeddings, attention modules, positional encodings, etc.). Great for bridging intuition and implementation.

- **[MayukhSobo / Transformer (GitHub)](https://github.com/MayukhSobo/Transformer)**  
  An “honest implementation” of a full encoder-decoder transformer, with modular components (self-attention, cross-attention, residual + norm layers), multiple tokenizers, WMT14 integration, and well-documented code.  
  I include this as a companion reference because it’s more production-minded (error handling, logging, modular design) while remaining readable. Use it to compare how you’d structure real-world code vs tutorial-level implementations.

---

## 📚 Deep Learning Reference Book

**[Deep Learning: Foundations and Concepts — Christopher M. Bishop & Hugh Bishop](https://www.bishopbook.com/)**  
This book goes beyond surface mechanics and helps you **really internalize** foundational ML / DL principles.  
It’s not just about architectures — it covers probability, optimization, theory, and enduring concepts (including transformers) in a way that still feels fresh.  


---

## 🗒️ Slides and Notes

[**My Annotated Slides**](#)  
These slides are mostly **screenshots and notes** from videos, talks, and our internal sessions.  
They’re annotated in real time during the discussions, so some context might be missing — use them as visual guides rather than full explanations.

- [Download Presentation Slides](../doc/Attention_Notes.pptx)
- [Download Hand Notes](../doc/AttentionNotes.pdf)