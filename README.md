# Exercises in gravitational wave parameter estimation

This repository contains a series of hands-on exercises designed to accompany the lectures on gravitational wave parameter estimation of the  [Prospects in Theoretical Physics 2025](https://www.ias.edu/pitp) program.

Each exercise is in its own folder, which includes:

- A Jupyter notebook with the exercise.
- A `requirements.txt` file listing the dependencies for that exercise.

We recommend using Miniconda to manage environments cleanly.

## Prerequisites

Before starting, make sure you have Miniconda (or Anaconda) installed.

[Download Miniconda here](https://docs.conda.io/en/latest/miniconda.html)

Choose the version for your operating system and Python 3.x. Follow the instructions to install it. Once installed, you’ll have access to the `conda` command in your terminal.

## Getting Started

1. Clone this repository:
```
git clone git@github.com:jroulet/pitp-pe-exercises.git
cd pitp-pe-exercises
```
2. Navigate to the folder for the exercise you want to do, for example:
```
cd 1-gaussian_noise
```
3. Create a new conda environment for that exercise:
```bash
conda create --name gaussian_noise_env pip
conda activate gaussian_noise_env
pip install -r requirements.txt
```
4. Launch Jupyter Notebook:
```bash
jupyter notebook
```

## Tips

- You might want to make a copy of each notebook and work on the copy. This will minimize git conflicts when updating the repository.
- To update your clone of the repository as more exercises are added:
```bash
cd path/to/pitp-pe-exercises
git pull
```
- To list all your conda environments:
```bash
conda env list
```
- To delete an environment:
```bash
conda remove --name gaussian_noise_env --all
```
- If `conda` is not recognized in your terminal, try restarting the terminal or ensure that Miniconda was added to your system PATH during installation.

## Questions?

Feel free to open an issue or reach out with questions.
