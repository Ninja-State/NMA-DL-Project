# Inferring Latent States with RNNs
## Neuromatch Deep Learning Project

These Colab Notebooks ([Notebook1](https://github.com/Ninja-State/NMA-DL-Project/blob/main/RNN_classifier_Steinmetz_dataset.ipynb), [Notebook2](https://github.com/Ninja-State/NMA-DL-Project/blob/main/t_SNE_Steinmetz_dataset.ipynb), [Notebook3](https://colab.research.google.com/github/eomorozova/NMA-DL-Project/blob/Katya/NMA_DL_Project.ipynb)) have the code to analyze [Steinmetz dataset](http://data.cortexlab.net/dualPhase3/) containing data from hundreds of simultaneously recorded neurons from multiple brain regions of mice completing a visual discrimination motor task.

We used seq-to-seq Recurrent Neural Networks (RNN) to examine the low-dimensional dynamics of the neural spiking activity in the Steinmetz data. We then used RNN with many-to-one architecture to predict the behavior of the mouse based on the spiking activity in Thalamus and explore its latent states.

We also used nonlinear embedding technique (t-SNE) to visualize neural activity patterns from Visual Cortex (V1) in response to stimuli of different intensities, as well as activity patterns from Thalamus during correct and incorrect trials. 

The results of the project are summarized [here](https://github.com/Ninja-State/NMA-DL-Project/blob/main/Ninja%20State%20Presentation.pdf)
