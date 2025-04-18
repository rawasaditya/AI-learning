## What is Machine learning
Machine learning is type of AI that learns from `A to B` or `Input to Output`

Example:
| Input (A) | Output (B) | Application|
|-----------|------------|------------|
| Email | Spam ? | Spam filtering
|Audio| Text Transcripts | Speech recogination|
| English | Chinese | Machine translation |
|ad, user info | Click ? | Online Advertising |
|inage, radar info | position of other cars | Self-driving car |
|Image of Phone | Defect ? | visual inspection |

Supervise learning also lies at the heart of generative AI systems, like ChatGPT and chat bots that generate texts. These systems work by learning from huge amount of texts. When you provide few text inputs model can predict the next word that comes after. These models are called Large language models (LLMs), generate new texts by repeatedly predeciting what is the next word they sould output.
<video src="assets/next-word-predection.mp4" width="100%" height="240" controls></video>

### How large language model (LLMs) work

In recent years, large language models (LLMs) like ChatGPT have taken the world by storm. From writing essays to generating code, these AI systems are becoming increasingly capable and useful. But how do they actually work? Let's break it down in simple terms.

---

## What Is a Large Language Model?

A large language model is an artificial intelligence system trained to understand and generate human language. It works by predicting the next word in a sentence, given the words that came before. Over time, by seeing countless examples, it learns the patterns of how language works.

---

## Learning by Prediction: The Core Idea

At the heart of an LLM is a simple task: **predict the next word**.

Imagine the sentence:
> "My favorite drink is lychee bubble tea."

This sentence is turned into multiple training examples:
- Input: "My favorite drink" → Output: "is"
- Input: "My favorite drink is" → Output: "lychee"
- Input: "My favorite drink is lychee" → Output: "bubble"
- Input: "My favorite drink is lychee bubble" → Output: "tea"

These input-output pairs (called A → B mappings) teach the model how to guess the next word.

This process is repeated **billions of times** using text from books, websites, conversations, and more. The more examples the model sees, the better it becomes at understanding how language flows.

---

## Supervised Learning: The Training Method

The technique used to train LLMs is called **supervised learning**, which means learning from labeled examples. In this case, the label is the correct next word.

The model is shown a phrase (input) and asked to predict the next word (output). If it gets it wrong, it adjusts its internal settings slightly. After repeating this process billions of times, it becomes very good at making predictions.

---

## Scaling Up: Why LLMs Are So Powerful

Two key factors have made LLMs incredibly powerful:

1. **More Data**: We now have access to vast amounts of digital text from across the internet.
2. **Bigger Models**: Advances in computing power allow us to train much larger neural networks.

As we feed more data into bigger models, something amazing happens: performance keeps improving. This is unlike older AI systems, which would eventually stop improving no matter how much data they were given.

---

## The Role of Neural Networks

LLMs use deep learning and neural networks to make sense of language. A neural network is a system of algorithms modeled after the human brain. It helps the AI learn complex patterns and relationships between words.

The bigger the neural network, the more patterns it can learn. That's why modern LLMs have **billions (or even trillions) of parameters**.

---

## Prompting the Model: How ChatGPT Responds

Once trained, an LLM like ChatGPT can take in a **prompt** (a few words or a sentence) and generate a logical continuation. For example:
> Prompt: "The capital of France is"
> → Completion: "Paris"

Because it has seen so many examples during training, the model can generate realistic and useful responses.

---

## Beyond Prediction: Fine-Tuning and Safety

After initial training, developers fine-tune the model to follow instructions better and avoid generating harmful or biased content. This process includes:
- Reinforcement learning from human feedback
- Safety layers and content filters

These steps help ensure the model is not only smart, but also responsible.

---

## Conclusion

Large language models work by learning to predict the next word in a sentence using supervised learning. While the concept is simple, when scaled up with massive data and powerful neural networks, it becomes incredibly effective.

These models are transforming industries, enabling new tools, and reshaping how we interact with technology. And at the heart of it all is a powerful idea: learning from data to understand and generate human language.

Stay tuned for more deep dives into how AI is shaping our future!