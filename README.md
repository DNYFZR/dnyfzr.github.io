<h2 align="center"><b> Development README </b></h2>

| **Build** | [![build](https://github.com/DNYFZR/dnyfzr.github.io/actions/workflows/build.yml/badge.svg)](https://github.com/DNYFZR/dnyfzr.github.io/actions/workflows/build.yml)
|--|--
| **Deployment** | [![pages-build-deployment](https://github.com/DNYFZR/dnyfzr.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/DNYFZR/dnyfzr.github.io/actions/workflows/pages/pages-build-deployment)

<br>

This project has been build using mkdocs & the mkdocs-material theme.

- The site is configured using the [mkdocs.yml](/mkdocs.yml)

- Site pages are managed via the [docs](/docs/) directory

- Build is managed via [GitHub Actions](https://github.com/DNYFZR/dnyfzr.github.io/actions)

<br>

Python has been used to create a development environment, and to install the mkdocs packages within it :

````ps1
# Set up & install
python -m venv <env_name>
cd <env_name>/scripts
./activate

python -m pip install -U pip
python -m pip install mkdocs mkdocs-material

# Setup project
cd ../../
mkdocs new <project_name>

# Launch mkdocs local server 
cd <project_name>
mkdocs serve

````
