# Empty Python Project template

This template is largely inspired from the Python Project Template made by the Scientific Software Center from Heidelberg University ([https://github.com/ssciwr/python-project-template/tree/main/src](https://github.com/ssciwr/python-project-template/tree/main/src))

## How to use this template

Create a new GitHub repository using this template and start coding!

Modify the following files to fit your project:

- pyproject.toml: project name, author, github url, dependencies, etc.
- requirements-dev.txt: dev dependencies for project development
- mkdocs.yml: documentation configuration
- docs/index.md: documentation homepage
- src/package_name: source code directory

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
