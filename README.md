# Empty Python Project template

This template is largely inspired from the Python Project Template made by the Scientific Software Center from Heidelberg University ([https://github.com/ssciwr/python-project-template](https://github.com/ssciwr/python-project-template))

## How to use this template

Create a new GitHub repository using this template and start coding!

Modify the following files to fit your project:

- pyproject.toml: project name, author, github url, dependencies, etc.
- requirements-dev.txt: dev dependencies for project development
- mkdocs.yml: documentation configuration
- docs/index.md: documentation homepage
- src/package_name: source code directory

For development, install the dev-dependencies by running:

```bash
pip install -r requirements-dev.txt
```

## Setting up documentation

From GitHub, go to the settings of your repository and enable GitHub Pages by chosing `Github Actions` as the source.
The documetation will be automatically build in your project page ([https://username.github.io/project_name/]) by the `deploy-docs.yml` GitHub Action when pusing a new commit (or accepting a Pull Request) to the main branch.

## Package installation

Clone the repository and go to the project directory

```bash
git clone [github url]
cd `package_name`
```

Create an anaconda environment and upgrade pip

```bash
conda create -n `package_name` python=3.9
conda activate `package_name`
python3.8 -m pip install --upgrade pip
```

Install `package_name` package and its dependancies by using pip

```bash
pip install -e .
```
