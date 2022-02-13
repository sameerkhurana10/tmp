# Due date: Feb 14, 2022 at 11:59 P.M.

# Student Name

Sameer Khurana

Kerberos: skhurana

# Lab 1: Neural Network Profiling and Inference

In this problem set, we will cover the basics of running neural network inference
in [PyTorch](https://pytorch.org/). PyTorch is a very popular
neural network framework maintained by Facebook, and it is used by a multitude of
researchers worldwide. Our goal will be to prototype networks for two classic
tasks: the MNIST digit recognition task and the ImageNet object classification
task. We will go through basic network inspection, inference and training in
these questions. Since the eventual goal of this course is to design hardware
for neural network inference, an important focus of this problem set will be to
develop a quantitative understanding of the computation involved in these tasks.

## Part 1: MNIST: PyTorch

The first task at hand is to familiarize ourselves with the PyTorch
framework. We will start with a very simple classification: digit classification
using the MNIST dataset. The MNIST dataset for this task consists of small
square images of handwritten digits from 0 to 9. The goal is to identify the
correct digit in every image. 

Answer the questions in the `workspace/lab1/1_pytorch.ipynb`.

## Part 2: MNIST: First Principles

In this part, our goal is to get a concrete understanding of the various
operations involved in neural network inference. To do this, we will rewrite the
network from Part 1 from first principles using Python and NumPy.

Answer the questions in the `workspace/lab1/2_first_principles.ipynb`.

## Part 3: ImageNet: AlexNet

In this part, our goal is to consolidate our understanding of inference using 
the AlexNet network for the the ImageNet task.

Answer the questions in the `workspace/lab1/3_alexnet.ipynb`.

## Submission
After finished the three notebooks, please commit and push the notebooks to the GitHub repo.
