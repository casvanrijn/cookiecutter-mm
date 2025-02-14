# Welcome

This is a project created with the mobiel meten cookiecutter. Here you find some basic
information about how to use a project created by this cookiecutter.

## Installation

To install {{cookiecutter.__project_slug}}, do:

### Conda 

    git clone https://gitlab.com/{{cookiecutter.gitlab_group}}/{{cookiecutter.__project_slug}}.git
    cd {{cookiecutter.__project_slug}}
    conda install --file "requirements.txt"

### pip

    git clone https://gitlab.com/{{cookiecutter.gitlab_group}}/{{cookiecutter.__project_slug}}.git
    cd {{cookiecutter.__project_slug}}
    pip install -r requirements.txt

## Run tests

### conda


    conda install --file "requirements.txt"
    pytest


### pip

    pip install -r requirements.txt
    pytest


