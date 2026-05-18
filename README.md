# Welcome to the REAME of the VHIO academy Introdcution to Deep Learning course!

You can find here the slides of the course, and the notebooks used during the course.

If you want to run the notebooks yourself, you need to install the tailored environment. As dependencies can be complex, I recomment ot use mamba instead of conda.

You also need to download the data:
https://drive.google.com/drive/folders/1HVNenrr-Sn1SkwO7g25N9hS-E9TSUbkd?usp=sharing


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
