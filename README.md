# ATTP-2025: Exploring artificial intelligence for (quantum) physics

This repository contains material for the second module of the [DRSTP](https://www.drstp.nl/) course ["Advanced Topics in theoretical Physics I: 2025"](https://www.drstp.nl/events/advanced-topics-in-theoretical-physics-autumn-2025/).

## About the course

This course is about *learning algorithms* for (quantum) physics. This includes machine learning for quantum control problems, reinforcement learning for quantum error correction, and a natural extension from reinforcement learning to quantum games and quantum game theory.


The goal of the course is to build an overview of the types of applications machine learning may have in physics, and to give you hands-on experience with it through interactive python notebooks. The lectures will introduce key concepts and will discuss the broader context.


After the course you will be able to assess whether your own research ideas are amenable to machine learning approaches, and to find and implement the right algorithms to try so.

## About the notebooks

The provided jupyter notebooks offer a hands-on literate programming way of getting to know basic machine learning concepts and see them in action. 

- [Notebook 1](https://github.com/everthemore/ATTP-2025/blob/main/ATTP_1.ipynb) provides an overview of using machine learning techniques to identify the critical point of the 2D Ising model.
- [Notebook 2](https://github.com/everthemore/ATTP-2025/blob/main/ATTP_1-2.ipynb) provides some dimensionality reduction and data visualization techniques as well as using a VAE for both the Ising model and the MNIST datase.

## Prerequisites & Installation

The repository contains `.ipynb` files so a familiarity with python is assumed. Moreover, knowledge of scientific and ML libraries such as `numpy` and `jax` is a bonus but not strictly nessecary.

> [!TIP]
> The recommended method would be running the notebooks on [google colab](https://colab.research.google.com/) to avoid having to deal with package installations. Navigate to Open notebook > Github > enter 'everthemore' in the search bar and open the notebook.

If you want to run the notebooks locally you can do so by cloning the repository with:

```
git clone https://github.com/everthemore/ATTP-2025
```

In that case, is recommeded that you create a virtual environment to download all the required dependencies:

```bash
# Create virtual environment
python -m venv notebook_env
# -- Activate it 
# Windows:
notebook_env\Scripts\activate
# Mac/Linux:
source notebook_env/bin/activate
# Install jupyter and common packages
pip install jupyter numpy matplotlib jax
# Install ipykernel
pip install ipykernel
# Add your venv to Jupyter as a kernel
python -m ipykernel install --user --name=notebook_env --display-name="Python (notebook_env)"
```

## Additional resources

The field is vast, mostly driven by the extraordinary success of machine learning in its own right. But as they say "when you have a hammer, everything looks like a nail" and physics problems seem to be a pretty good nail.
Here are some extra resources for any intersted student that wants to delve more into the merging of machine learning and physics

- [A high-bias, low-variance introduction to Machine Learning for physicists](https://arxiv.org/pdf/1803.08823): Seminal paper for general ML
- [Attention is all you need](https://arxiv.org/pdf/1706.03762): Perhaps the ML paper of the decade
- [Interpretable machine learning for physics: A review](https://arxiv.org/pdf/2503.23616): Recent review paper for ML+Physics
- [Welch Labs](https://www.youtube.com/channel/UConVfxXodg78Tzh5nNu85Ew): Excellent youtub channel for various ML/Physics topics
- [AlexNet-Welch Labs](https://www.youtube.com/watch?v=UZDiGooFs54&t=915s): Building intuition on CNNs
- [Learnin phase transitions by confusion](https://www.nature.com/articles/nphys4037): Unsupervised method for learning phase transitions
- [Machine learning and the physical sciences](https://arxiv.org/pdf/1903.10563): Another seminal paper on ML+Physical sciences
- [Quantum computing and artificial intelligence: status and perspectives](https://arxiv.org/pdf/2505.23860): Big collaboration of many scientists for ML+QC
- [The principles of deep learning](https://arxiv.org/pdf/2106.10165): For those with a QFT background that want to delve deeper into Deep learning
- [Structures of Neural Network Effective Theories](https://arxiv.org/pdf/2305.02334): Some more QFT+NN magic
- [Stanford CS229: Machine Learning Course](https://www.youtube.com/watch?v=jGwO_UgTS7I&list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU): Amazing ML course by one of the leaders of the field
- [Geoffrey Hinton](https://scholar.google.com/citations?user=JicYPdAAAAAJ&hl=en): One of the founding fathers of the field, many seminal papers are listed in his google scholar
