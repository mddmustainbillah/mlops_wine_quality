Create environment

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

created a req file

install the req
```bash
pip install -r requirements.txt
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
git commit -m 'first commit'
```
Onliner updates for README
```bash
git add . && git commit -m 'update README.md'
```
```bash
git remote add origin https://github.com/mddmustainbillah/mlops_wine_quality.git
git branch -M main
git push -u origin main
```


Run all the code:
```bash
dvc repro
```

See the metrics difference
```bash
dvc metrics diff
```

tox command - 
```bash
tox
```
For rebuilding -
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
Build your own package command:
```bash
python setup.py sdist bdist wheel
```



