# Lesson Notes: Secure and Private AI

This is my personal notes from the course of udacity [Secure and Private AI](https://eu.udacity.com/course/secure-and-private-ai--ud185) part of the [Facebook Scholarship Challenge](https://eu.udacity.com/facebook-AI-scholarship). These notes are forked from the original repository of the course but with some comments and notes added.

## How to use the Jupyter Notebooks in this repository

### Open In Google Colab

Every Notebook will have a badge at the top called *Open in Colab*. To run in Google Colab you can click on the button that will look like this:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]( https://colab.research.google.com/github/MarianoOG/Lesson-Notes-Secure-and-Private-AI)

### Run locally

The easiest way to install the required libraries is with [Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/overview.html). Create a new environment, then install the dependencies in that environment. To run these notebooks you'll need to install Python 3.6+, PySyft, Numpy, PyTorch 1.0, and Jupyter Notebooks.

In your terminal:

```bash
conda create -n pysyft python=3
conda activate pysyft
conda install numpy jupyter notebook
conda install pytorch torchvision -c pytorch
pip install syft
pip install numpy
```

If you have any errors relating to zstd - run the following (if everything above installed fine then skip this step):

```
pip install --upgrade --force-reinstall zstd
```

and then retry installing syft (pip install syft).

If you are using Windows, I suggest installing [Anaconda and using the Anaconda Prompt](https://docs.anaconda.com/anaconda/user-guide/getting-started/) to work from the command line. 

With this environment activated and in the repo directory, launch Jupyter Notebook:

```bash
jupyter notebook
```

and re-open this notebook on the new Jupyter server.

If any part of this doesn't work for you (or any of the tests fail) - first check the [README](https://github.com/OpenMined/PySyft.git) of PySyft repository for installation help and then open a Github Issue or ping the #beginner channel in Open Mined slack: [slack.openmined.org](http://slack.openmined.org/)

## #60DaysOfUdacity

I will use this repository to elaborate on the challenges as well as other ideas related to the course. My progress day by day is written in the [#60DaysOfUdacity](60DaysOfUdacity.md) list which is one of the initiatives of the course.

You can also follow the progress in [twitter](https://twitter.com/Mariano_OG/status/1145344794690031619?ref_src=twsrc%5Etfw").
