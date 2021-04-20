# Exploring Deep Generative Sketch Networks

All the code and resources here have one goal, satisfying our curiosity. I conduct field studies to explore the possible improvements in deep generative models. What do humans expect from a reconstruction task? What are the expectations from interpolation? ... If we can answer these questions, we can answer meaningful metrics for generative techniques. I believe that current sketch models focus too much on popular models produced in the image generation area. But, image is a more objective area. The end result is an output of a machine. Sketching is a unique process for each of us.

Let's first explore the recent generative models. We picked four generative models: Autoencoder, DCGAN, SketchRNN and Sketchformer. The first two take pixel values and the last two take stroke-based representations. We will use Quick, Draw! dataset in our training process. I think it is not an ideal dataset, but this is the best sketching dataset until someone comes with a better one. By the way, playing with Quick, Draw! dataset is extremely fun. I only think that it is not the most representative dataset to train generative models.

To understand the area, you can check the following work. I strongly recommend playing with the explorables to better understand the possibilities. You can also think of that as a fun EDA to explore Quick, Draw! dataset.

## Explorables on Quick, Draw!

- [Finding Bad Flamingo Drawings](http://colinmorris.github.io/blog/bad_flamingos)0
- [How Long Does it Take to (Quick) Draw a Dog?](http://vallandingham.me/quickdraw/)
- [Magenta - SketchRNN Demos - Draw Together with a Neural Network](https://magenta.tensorflow.org/sketch-rnn-demo)
- [Visualizing the Latent Space of Vector Drawings from the Google QuickDraw Dataset with SketchRNN, PCA and t-SNE](http://louistiao.me/posts/notebooks/visualizing-the-latent-space-of-vector-drawings-from-the-google-quickdraw-dataset-with-sketchrnn-pca-and-t-sne/)

## Explorables on Representation Visualization

- [Visualizing Representations: Deep Learning and Human Beings](http://colah.github.io/posts/2015-01-Visualizing-Representations/)
- [Visualizing Autoencoders with Tensorflow.js](https://douglasduhaime.com/posts/visualizing-latent-spaces.html)
- [How to Use t-SNE Effectively](https://distill.pub/2016/misread-tsne/)
- [Towards an Interpretable Latent Space](https://thilospinner.com/towards-an-interpretable-latent-space/)

## What can you find in our repo?

- **Reconstruction study**: If you find this repo by reading our [preprint](./), you might want to check our [notebooks](./notebooks/) or [reconstruction data](./data/sketch-order.csv). 
- **Clustering study**: It is still a work in progress. Actually, all the repo is a work in progress, I am still managing to find the best way to present all the work...
- **Read our content**: 
    - [Review of generative sketch models](https://asabuncuoglu13.github.io/sketch-embeddings/docs/index.html), 
    - [A Critical Evaluation of Recent Deep Sketch Models' Reconstruction Abilities](), 
    - [Using Latent Space Visualization to Control Sketch Interpolation]() 

