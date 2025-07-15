# Causal AI

This repo will be implementing certain chapters of the book [causal AI](https://www.manning.com/books/causal-ai).The book was written by [Robert Osazuwa Ness, Ph.D](https://www.microsoft.com/en-us/research/people/robertness/) a senior reasearcher at Microsoft Research AI foucusing on "statistical techniques for advancing LLM control and robustness." Modeling causality using deep learning will become ever more important to make AI more explainable and trustable than it currently is. Others in the industry have taken notice of this  and view causal AI as an [emerging technology](https://www.weforum.org/stories/2024/04/causal-ai-decision-making/#:~:text=Causal%20AI%2C%20an%20emerging%20field%20that%20focuses,underlying%20causal%20structures%20that%20govern%20the%20world.) that will allow AI to become more ubiquitous in safety critical areas. This repo will be updated as I read more of the book and will feature the chapters that I feel are very relevant to the future research and development of deep learning models that incorporate causal reasoning. 

## Ch. 5 - Connecting Causality and Deep Learning

The colab notebook [Ch5CausalDeepLearning](https://github.com/AdamClarkStandke/CausalAI/blob/main/Ch5CausalDeepLearning.ipynb) implements the design, intuition and training of a causal VAE when it comes to generating and dealing with high-dimensional data such as images. The causal model of this data generation process takes the form of labels and latent factors being the causes of the generated images.

## Ch. 9 - General Counterfactual Inference Algorithm

The colab notebook [Ch9CausalDeepLearning](https://github.com/AdamClarkStandke/CausalAI/blob/main/Ch9_General_CounterFactual_Inference.ipynb) implements chapter 9 of the book which deals with the general algorithm of probabilistic counterfactual inference. The general algorithm consists of the steps of Abduction, Action and Prediction. This notebook implements two of the practical examples of the book. The first example deals with predicting a person's height and uses the steps of the algorithm to answer a conditional hypothetical and a parallel-world counterfactual. The second example deals with implementing the algorithm to do semantic editing of a 2d sprite image.    


