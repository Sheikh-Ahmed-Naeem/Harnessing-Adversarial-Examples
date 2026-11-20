# Harnessing-Adversarial-Examples


1. Train a small MNIST classifier and implement the fast gradient sign method from
the paper.
2. Reproduce the error-rate-versus-𝜀 relationship, and show the perturbed images
alongside the originals at the 𝜀 where accuracy collapses.
3. Reproduce transferability. Craft adversarial examples against model A, evaluate
them on a separately trained model B. The paper’s linear explanation predicts this
should work; check whether it does.
4. Implement the adversarial training objective and report both what robustness it
buys and what it costs in clean accuracy.
