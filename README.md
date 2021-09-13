conda create -n MLOPS

conda activate MLOPS

pip install -r requirements.txt

<!-- For Creating Folder Structure -->
python template.py 

<!-- Download git from git-scm.com/downloads -->

git init

dvc init

dvc add data_given\winequality.csv

```bash
git add .
git commit -m "First Commit"
git remote add origin https://github.com/ManiKumarB/MLOPS.git
git branch -M main
git push origin main
```


```bash
dvc repro
dvc metrics show
dvc metrics diff
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
setup commands -
```bash
pip install -e . 
```
build your own package commands-
```bash
python setup.py sdist bdist_wheel
```