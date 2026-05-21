# Welcome to the README of the VHIO academy Introduction to Deep Learning course!

You can find here the slides of the course and the notebooks used during the course.

If you want to run the notebooks yourself, you need to install the tailored environment. As dependencies can be complex, I recommend using mamba instead of conda.

You also need to download the data:
https://drive.google.com/drive/folders/1HVNenrr-Sn1SkwO7g25N9hS-E9TSUbkd?usp=sharing

If you do not succeed in setting up the environment, you can run the notebooks in Google Colab, but it's a good exercise to create the environment, and it will give you more flexibility to play with the notebooks!

Follow the explanations:

# Environment install:

## 0) Install micromamba (recommended, otherwise you can use conda)

Follow the tutorial here depending on your OS:

`https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html`

## 1) Confirm installation
To confirm micromamba is installed correctly:

`micromamba --version`

## 3) Create the environment from YAML
Recommended:

`micromamba create -f DL_intro_env.yml`

or 

`conda env create --file DL_intro_env.yml`

## 4) Activate the environment
`micromamba activate DL_intro_VHIO`

or

`conda activate DL_intro_VHIO`

## 5) Add the environment to the path
Sometimes your notebook runner (VS Code or Jupyter) does not automatically recognise the new environment. You need to run

`python -m ipykernel install --user --name DL_intro --display-name "Python (DL intro)"`

You can change the displayed name.

