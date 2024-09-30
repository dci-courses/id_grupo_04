# repo


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

This file will become your README and also the index of your
documentation.

## Developer Guide

If you are new to using `nbdev` here are some useful pointers to get you
started.

### Setup

It can be helpful to have a dedicated environment for development. Here
we are assuming that you have an conda environment file called `env.yml`
named after `repo` i.e.:

``` yaml
# env.yml
name: repo

channels:
  - fastai

dependencies:
  - fastai::nbdev>=2.3.12
# - python>=3.11  # specify python version if required 
# - dependency 1
# - dependency 2
# - pip
# pip:
#   - pip dependency 1
#   - pip dependency 2
```

You can then use `conda` or `mamba` (faster at resolving) to create and
update your environment file should your needs change as you work on
`repo`

``` sh
# create a conda environment for working on repo
$ mamba env create -f env.yml

# update conda environment
$ mamba env update -n repo --file env.yml
```

### Install repo in Development mode

``` sh
# activate conda environment
$ conda activate repo

# make sure repo package is installed in development mode
$ pip install -e .

# make changes under nbs/ directory
# ...

# compile to have changes apply to repo
$ nbdev_prepare
```

## Usage

### Installation

Install latest from the GitHub
[repository](https://github.com/user/repo):

``` sh
$ pip install git+https://github.com/user/repo.git
```

or from [conda](https://anaconda.org/user/repo)

``` sh
$ conda install -c user repo
```

or from [pypi](https://pypi.org/project/repo/)

``` sh
$ pip install repo
```

### Documentation

Documentation can be found hosted on this GitHub
[repository](https://github.com/user/repo)’s
[pages](https://user.github.io/repo/). Additionally you can find package
manager specific guidelines on [conda](https://anaconda.org/user/repo)
and [pypi](https://pypi.org/project/repo/) respectively.

## How to use

Fill me in please! Don’t forget code examples:

``` python
1+1
```

    2
