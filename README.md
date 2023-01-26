# Minifigures Webshop

## Welcome! 👋

Welcome to the *Minifigures Webshop* project assignment. The goal of this assignment is to teach the students everything they need to develop and deploy an AI solution from start to finish. For this project, you're going to learn how to create your own *Amazon.com* or *bol.com* like webshop, focussed on LEGO minifigures.

![Webshop Example](https://www.sendcloud.nl/wp-content/uploads//2018/04/Amazon-prime.png)

If you're curious how the final result will look like, go and visit our [reference solution](http://realization-of-ai.radix.sh)!



## Getting Started 🚀

### Fork this repository

To start with this assignment, you need to fork this repository to create your own, personal and private, repository.

### Open in GitHub Codespaces

We recommend to develop in [GitHub Codespaces](https://github.com/features/codespaces), which will automatically open the pre-configured environment so that you can start coding immediately! Click on _Code_ and select _Create codespace_ to start a Dev Container GitHub Codespaces. By default, it will spin up a compute instance with a 2-core CPU, 4GB of RAM, and 32GB of storage. This is enough for this project and also the advised configuration since it prevents you from running out of core hours (240h/month for students).


## Development tools 🛠️

### Poetry

This repository utilises on [Poetry](https://python-poetry.org/), an environment that aims to make Python packaging and dependency management as easy as possible. To get you started, we've added all necessary requirements in the `pyproject.toml` file. However, in case you want to add other packages, you can do so using `poetr add {package}` from within the development environment. Add `--group {train|test|dev}` to install the dependency as a training, testing/linting, or development dependency. You can alos removing packages from your environment using `poetry remove {package}`.Run `poetry update` from within the development environment to upgrade all dependencies to the latest versions allowed by `pyproject.toml`.

### Poe the Poet

To make the development of your code go more efficiently, we've included a virtual assistant; [Poe the Poet](https://github.com/nat-n/poethepoet)! Run `poet` from within the development environment to see what it can do. A short summary of the available commands:

- `poe api` to run the REST API (found in the `src/minifigures_api/` folder)
- `poe app` to serve the Streamlit application (found in the `src/minifigures_app/` folder)
- `poe lint` to run the linting checks and fixes over your code
- `poe test` to test your code

