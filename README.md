## README

| **Status** | [![pages-build-deployment](https://github.com/DNYFZR/dnyfzr.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/DNYFZR/dnyfzr.github.io/actions/workflows/pages/pages-build-deployment)
|--|--

This repo hosts my [GitHub Pages site](https://DNYFZR.github.io/)

- The site is configured using the [mkdocs.yml](/mkdocs.yml)

- Site pages are managed via the [docs](/docs/) directory

- Build is managed via [GitHub Actions](https://github.com/DNYFZR/dnyfzr.github.io/actions)

### Site Build

This project has been build using mkdocs & the mkdocs-material theme.

````ps1
# Set up & install
python -m venv <env_name>
cd <env_name>/scripts
./activate

python -m pip install -U pip
python -m pip install mkdocs

# Setup project
cd ../../
mkdocs new <project_name>

# Launch mkdocs local server 
cd <project_name>
mkdocs serve

````
