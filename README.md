# cs231n-vision-transformers-plant-traits
### **Ensemble Vision Transformers for Plant Traits Prediction**, Stanford CS 231N Final Project 2024.

By **Lisa Fung** (lisafung@stanford.edu) and Annabelle Aurelia Jayadinata

Our project serves as an entry for the [Kaggle competition PlantTraits2024 - FGVC11](https://www.kaggle.com/competitions/planttraits2024/), which aims to “advance
our understanding of the global patterns of biodiversity.”

We achieved $R^2 = 0.346$ with Ensemble Vision Transformer architecture combining Vision and Swin Transformer models

### Poster
![Poster_Vision_Transformers_Plant_Traits](https://github.com/lfun1/cs231n-vision-transformers-plant-traits/assets/71937811/a145e4b1-671c-4c59-8734-15e7eff9aa7f)

### Abstract
Gathering comprehensive data on plant traits is key to understanding how plants and entire ecosystems are adapting to climate change. Currently, there is very little data on plant traits. Our goal is to predict a broad set of 6 plant traits (leaf area, plant height, specific leaf area, leaf nitrogen concentration, seed mass, and stem specific density) from crowd-sourced plant images and some ancillary data. Their traits hold the key to understanding ecosystems, e.g., in terms of their diversity, productivity, or how these plants face the challenges brought on by climate change. We applied state-of-the-art image classification architectures and developed a fine-tuned ensemble transformer architecture with the Vision Transformer and Swin Transformer for solving this problem. Using a _SmoothL1Loss_ loss function, we achieved a final $R^2$ score of $0.346$ on the test set. We showcase visualizations of the transformer model on a variety of input images to validate that the model is generalizing well to the plant traits for each image.
