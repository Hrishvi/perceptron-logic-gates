# Perceptron from Scratch

> The simplest possible neural network — built from scratch so you can see exactly how it thinks.

If you've ever wondered *"how does a neural network actually learn?"* — this project answers that question with the most minimal, readable code possible.

No TensorFlow. No PyTorch. No magic. Just Python.

---

## What's a Perceptron?

Think of it like a student taking a true/false quiz.

1. It makes a **guess**
2. It checks if it was **right or wrong**
3. It **adjusts** so it does better next time
4. It repeats until it **gets every answer right**

That's literally it. And it's the same core idea behind every AI model you've ever heard of.

---

## What Does It Learn?

This perceptron learns **logic gates** — simple rules like:

| Gate | Rule |
|------|------|
| `AND` | Output 1 only if **both** inputs are 1 |
| `OR` | Output 1 if **either** input is 1 |
| `NOR` | Output 1 only if **both** inputs are 0 |

Three pre-trained models are included, ready to use.

---

## Try It Yourself

**Want to watch it learn in real time?**
```bash
python Perceptron_Training_.py
```
You'll see every guess, every mistake, and every correction as it trains.

**Want to test a pre-trained model?**
```bash
python Perceptron_Testing_.py
# When prompted, enter: AND_Gate_Model / OR_Gate_Model / NOR_Gate_Model
```

---

*The best way to understand neural networks is to build one yourself.*
