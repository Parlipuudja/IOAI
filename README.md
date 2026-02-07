# IOAI

*This README.md file is 95% Claude-generated, with human-made adjustments and a "What I learned" section*

Study and solution notebooks for the International Olympiad on AI (IOAI) — covering adversarial attacks on computer vision models, low-resource NLP, and fairness in word embeddings.

## Motivation

Preparing for the IOAI meant tackling research-level AI problems under time pressure. These notebooks are my sandbox for working through the competition challenges: breaking neural networks with adversarial examples, teaching a model to inflect Navajo verbs, and detecting gender bias baked into word vectors. Each challenge pushed into a different corner of modern AI.

## Challenges

- **Adaptive Attacks on CV Models** — reverse-engineer a defense (ensemble of 3 ResNets with majority voting) and craft targeted adversarial examples within an L-infinity budget of 8/255 on CIFAR-10
- **Morphological Inflection in Navajo** — modify the attention mechanism of a T5 seq2seq model to generate correct word forms in a low-resource setting (5,000 training samples)
- **Bias in Word Embeddings** — detect and analyze gender stereotypes in GloVe vectors using custom similarity metrics, vector geometry, and word analogy tests

## Tech Stack

| Component | Technology |
|-----------|-----------|
| Language | Python 3 |
| Deep Learning | PyTorch |
| NLP Models | Transformers (T5) |
| Embeddings | GloVe word vectors |
| Numerical | NumPy, SciPy |
| Environment | Jupyter Notebooks, Google Colab |

## Project Structure

```
├── IOAI_Adaptive_Attacks_(on_site).ipynb        # Adversarial attack challenge
├── IOAI_Morphological_Inflection_On_site_Task.ipynb  # Navajo NLP challenge
├── OS_IOAI_Biased_Embeddings.ipynb              # Bias detection (base)
├── OS_IOAI_Biased_Embeddings_2.ipynb            # Bias detection (v2)
├── OS_IOAI_Biased_Embeddings_completed.ipynb    # Completed solutions
└── OS_IOAI_Biased_Embeddings_very_completed.ipynb  # Extended solutions
```

## What I Learned

- **Nothing worthwhile is easy** - the whole "being a competitor for the 1st IOAI Bulgaria" was the hardest self-imposed strugge I've been through in my life. Learning that much AI didn't "simply" broaden my perspective in that and science altogether, but also changed my worldview completely. It's very hard to put into words, and ever harder to put it into text. 

- **The medal was silver, and the friends were gold** - my remake of what Ali Sharifi, the head of the ISC for IOAI, himself an IOI gold medalist, said at the closing ceremony. 