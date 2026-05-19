# PyTorch from scratch

14-day learning journal — ~15 minutes a day. Covers tensors, autograd, neural networks, and ends with a working MNIST classifier.

## Structure

```
pytorch-learning/
├── week1/
│   ├── day01_tensors.ipynb
│   ├── day02_tensor_ops.ipynb
│   ├── day03_autograd.ipynb
│   ├── day04_linear_model_by_hand.ipynb
│   ├── day05_nn_module.ipynb
│   ├── day06_loss_and_optimizers.ipynb
│   └── day07_project_linear_regression.ipynb
└── week2/
    ├── day08_dataloader.ipynb
    ├── day09_mlp.ipynb
    ├── day10_training_loop.ipynb
    ├── day11_overfitting_regularization.ipynb
    ├── day12_saving_loading_models.ipynb
    ├── day13_cnn_intro.ipynb
    └── day14_project_mnist.ipynb
```

## Curriculum

### Week 1 — foundations

| Day | Topic |
|-----|-------|
| 1 | Tensors — create, reshape, index, CPU vs GPU |
| 2 | Tensor operations — math, broadcasting, in-place |
| 3 | Autograd — requires_grad, backward(), reading .grad |
| 4 | Linear model by hand — manual gradient descent |
| 5 | nn.Module — wrapping models in a class |
| 6 | Loss functions & optimizers — MSE, CrossEntropy, Adam |
| 7 | **Project** — linear regression on a toy dataset |

### Week 2 — building real models

| Day | Topic |
|-----|-------|
| 8 | DataLoader & Dataset — batching and shuffling |
| 9 | Multi-layer perceptron — stacking Linear + ReLU |
| 10 | Training loop pattern — train/eval, zero_grad, step |
| 11 | Overfitting & regularization — Dropout, weight decay |
| 12 | Saving & loading — state_dict, torch.save/load |
| 13 | CNN intro — Conv2d, MaxPool2d, understanding shapes |
| 14 | **Project** — MNIST classifier, target >95% accuracy |

## Setup

```bash
pip install torch torchvision
```

Or use [Google Colab](https://colab.research.google.com/) — no setup needed and free GPU available.

## Progress

- [x] Day 1
- [ ] Day 2
- [ ] Day 3
- [ ] Day 4
- [ ] Day 5
- [ ] Day 6
- [ ] Day 7
- [ ] Day 8
- [ ] Day 9
- [ ] Day 10
- [ ] Day 11
- [ ] Day 12
- [ ] Day 13
- [ ] Day 14
