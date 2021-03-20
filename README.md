create env
```bash
conda create -n wineq python=3.6 -y
```

activate env
```bash
activate wineq
```
created a req file

install the req
```bash
pip install -r reqruirements.txt
```

```bash
download the data from 
```

```bash
shared git link 
```

```bash
git init
```

```bash
dvc init
```

```bash
dvc add data_given/winequality.csv
```

```bash
git add . 
```

```bash
git commit -m "first commit"
```

onliner updates for readme
```bash
git add . && git commit -m "update readme.md"
```

```bash
git remote add origin https://github.com/TousifAhamed/simple-dvc-demo.git
```
```bash
git branch -M main
```
```bash
git push -u origin main
```
tox command - 
```bash
tox
```
for rebuilding -
```bash
tox -r
```

pytest command
```bash
pytest -v
```

setup command -
```bash
pip install -e .
```

build your own package command - 
```bash
python setup.py sdist bdist_wheel
```