**Name: Sajitha Konda**
**Student Id: 700782694**

Project Overview & Functionality

**HOMEWORK 1**
Q1 — Regular expressions. Six patterns for ZIP codes, numeric formats, spelling variants of "email," and line anchoring. Each is tested against deliberate near-misses, since the difficulty lies in what a pattern must reject.
Q2 — Byte Pair Encoding. First three merges worked by hand, then a mini-BPE learner that verifies them and trains further. Reports the winning pair and vocabulary size per step, and flags ties. Segmenting unseen words (widest, newestest) shows why BPE has no out-of-vocabulary case: every character stays in the vocabulary, so segmentation cannot fail.
Q3 — Bayes' Rule. Prior, likelihood, and posterior interpreted for document classification, plus the argument for dropping P(d): it is constant across classes, so it cannot change the argmax.
Q4 — Add-1 smoothing. Smoothed likelihoods for the worked sentiment example, including the zero-count case that motivates smoothing , one unseen word would otherwise zero out an entire class.
Q5 — Tokenization. One paragraph tokenized three ways (whitespace, hand-corrected, NLTK) with disagreements printed. Cases like 3.5% and directional quotes differ by design decision, not error. Includes multiword expressions and the case for treating each as one token.
