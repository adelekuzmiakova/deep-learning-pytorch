# Introduction to Deep Learning with PyTorch

These are notes from Introduction to Deep Learning with PyTorch. If you need to access the materials, clone this repository using
```bash
$ git clone git@github.com:adelekuzmiakova/deep-learning-pytorch.git
```
and `cd` into it.


## Install PyTorch with Python3 Virtualenv Setup

A [Virtualenv](https://virtualenv.pypa.io/en/stable/) is a tool to keep the dependencies required by different projects in separate places by creating virtual Python environments for them. It solves the “Project X depends on PyTorch version 0.x but Project Y needs 1.x” dilemma and keeps your global site-packages directory clean and manageable.
 
 
### 1) Requirements
* Python 3
* Pip 3

```bash
$ brew install python3
```


Pip3 is installed with Python3


### 2) Installation
To install virtualenv via pip run:
```bash
$ pip3 install virtualenv
```


### 3) Usage
Creation of virtualenv:
```bash
$ virtualenv -p python3.5 [desired-path]
```
e.g.

```bash
$ virtualenv -p python3.5 .env
```

Activate the virtualenv:
```bash
$ source [desired-path]/bin/activate
```

e.g.

```bash
$ source .env/bin/activate
```

Within the virtualenv you can install project-specific packages:

```bash
$ pip3 install -r requirements.txt
```

When you are done working on your project, deactivate the virtualenv:
```bash
$ deactivate
```
