create env
```bash
conda create -n wineq python=3.11 -y
```

activate env
```bash
activate wineq
```
created a req file

install the req
```bash
pip install -r requirements.txt
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

## Running the web app
```bash
python app.py
```
Then open http://localhost:5000.

| Environment variable | Purpose | Default |
|---|---|---|
| `FLASK_DEBUG` | `1` turns on the Flask debugger and auto-reload. **Local development only**: the app listens on `0.0.0.0`, and the debugger would let anyone on the network run code. | off |

```bash
FLASK_DEBUG=1 python app.py      # macOS/Linux, local development
```
