# Capsule-Net-TF

A tiny implementation of the recently published Capsule Network by G.Hinton and colleague ( [paper link](https://arxiv.org/pdf/1710.09829.pdf) )

 * A novel concept of 'Capsules' which is basically vector-neurons as opposed to scalar neurons (the familier ones)
 * A routing algorithm (refer paper)
 * a not-so-deep network of capsules and normal convolutions
 * state-of-the-art performance on MNIST

## My implementation is still running on a 1050-TI GPU and hopefully is correct. I will add the results as soon as I can

| Epoch-1 | Epoch-2 | Epoch-3 |
| ------- | ------- | ------- |
|  96.2%  |  98.27  |  98.82  |

A screenshot from tensorboard

![loss](./results/loss_till_2k.png)

### Although, my goal is not to achieve highest test-accuracy but to understand the dynamics of the network and the capsules
