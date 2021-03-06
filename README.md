# 🧑‍🍳 The Data Science Kitchen Cookbook

This is a living document where we try to capture all learnings from past projects. Many things can qualify as a learning: a nasty bug that was discovered and fixed, unexpected or unusual behaviour of a model and the reason for it, a cool new tweak that gave an additional boost to model performance and generally everything that can be a helpful hint for future projects.

## List of past projects

- [GermEval 2021](#germeval-2021)

## GermEval 2021

### 📑 Project description

We submitted a contribution to the [GermEval 2021 Shared Task](https://germeval2021toxic.github.io/SharedTask/) on identifying toxic, engaging, & fact-claiming comments.

### 🥣 Recipes

- [Data augmentation](https://amitness.com/2020/05/data-augmentation-for-nlp/) can help for NLP tasks.
- How to come up with the best **hand crafted task specific features**? 👉 Infer as much as possible about the manual label strategy from the invitation paper and read around 100 comments of each label type to develop own theories about what could be useful features. Then test them
- Do **object oriented** programming for a modular **pipeline architecture** (Features and models as objects)
- Gather and load **run-parameters with a logger file** for fast trails and easy documentation
- Strive for the **simplest solution first** with minimal number of features and minimal ML model complexity (Naive Bias, logistic regression, SVM, Transformer... DNN...). Diligently **validate each addition** by checking whether it is yielding in an enhancement for the final score or not. As a side effect you get a nice and informative story telling about the solution process for the paper 🤓
