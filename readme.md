<br/>
<p align="center">
  <a href="https://github.com/dzalhaqi/pa-mlops">
  <h3 align="center">
    FastAPI Project
  </h3>

  <p align="center">
    Learn Dependency Injection and Inversion of Control in FastAPI by Building Online Recipe System Prototype
    <br/>
  </p>
  <p align="center">
    <a href="https://dzalhaqi.github.io/api-docs-online-recipe-system/">
      View API docs
    </a>
  </p>
</p>

<p align="center">
  <p align="center">
    <img src="https://img.shields.io/github/downloads/dzalhaqi/fastapi-online-recipe-system/total"/>
    <img src="https://img.shields.io/github/contributors/dzalhaqi/fastapi-online-recipe-system?color=dark-green"/>
    <img src="https://img.shields.io/github/forks/dzalhaqi/fastapi-online-recipe-system?style=social"/>
    <img src="https://img.shields.io/github/issues/dzalhaqi/fastapi-online-recipe-system"/>
    <img src="https://img.shields.io/github/license/dzalhaqi/fastapi-online-recipe-system"/>
  </p>
</p>

## Table Of Contents

- [Table Of Contents](#table-of-contents)
- [About The Project](#about-the-project)
  - [Description](#description)
  - [Preview API Docs (using Redocly)](#preview-api-docs-using-redocly)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About The Project

### Description
This API Project, is a API prototype known as the "Online Recipe System." This system is designed to effectively manage, evaluate, rate, and generate reports for recipes of diverse types and origins. The project emphasizes the implementation of a Dependency Injection (DI) pattern, which may lead to alterations in development strategies and approaches, including the incorporation of model, repository, and service folders. The software targets food enthusiasts and chefs seeking to share their culinary expertise, newcomers searching for recipes to experiment with, as well as guests who simply enjoy exploring various food menus. **As of now, this versatile application does not utilize any database management system; instead, all data is temporarily stored in Python containers.** 

### Preview API Docs (using Redocly)



## Built With

Application deployed is build with **Python** using **FastAPI** library 

## Getting Started

To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to list things you need to use the software and how to install them.

* python

for Windows OS
```sh
python --version 
```

for Unix Based OS (Linux, MacOS, etc)
```sh
python3 --version 
```

* git

```sh
git --version 
```

> note: if you don't have python installed, you can download it [here](https://www.python.org/downloads/) and if you don't have git installed, you can download it [here](https://git-scm.com/downloads)

### Installation

1. Clone the repo

```sh
git clone https://github.com/Dzalhaqi/fastapi-online-recipe-system.git
```

2. Create python environment

```sh
python -m venv env
```

3. Activate python environment

* for Windows OS
```sh
env\Scripts\activate
```

* for Unix Based OS (Linux, MacOS, etc)
```sh
source env/bin/activate
```

4. Install python library

```sh
pip install -r requirements.txt
```

5. Run the FastAPI server with uvicorn (default port 8000)

```sh
uvicorn main:app --reload
```

## License

Distributed under the MIT License. See [LICENSE](https://github.com/dzalhaqi/pa-mlops/blob/main/LICENSE.md) for more information.

## Acknowledgements

* [Muhammad Dzalhaqi](https://github.com/dzalhaqi/)
