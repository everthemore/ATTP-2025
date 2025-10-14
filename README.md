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
