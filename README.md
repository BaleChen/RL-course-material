# Reinforcement Learning Algorithm Notebooks

This repository contains course materials I developed for NYU Shanghai's Fall 2023 CSCI-375 Reinforcement Learning class. The notebooks are mainly used for in-class demonstration and homework. Please feel free to contact me for any questions or issues. If you would like to adapt the code for other purposes, please kindly notify me through email ``(bale[dot]chen[at]nyu[dot]edu)`` and cite properly.

For `notebooks/dqn-atari.ipynb`, `notebooks/dqn-lunar.ipynb`, `notebooks/policy_gradient.ipynb` and `ppo.ipynb`, you can run them on Google Colab with a GPU. The others can be run on CPU within a reasonable amount of time.

## Setup

Run the following commands to create a minimal conda environment to run the notebooks in this repo.

```
git clone https://github.com/BaleChen/RL-course-material.git
cd RL-course-material

conda create -n your-env-name python=3.10
conda activte your-env-name
pip install -r requirements.txt
```

Then, you can run the python notebooks in your preferred IDE.