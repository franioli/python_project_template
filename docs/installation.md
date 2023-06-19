# Package installation

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
