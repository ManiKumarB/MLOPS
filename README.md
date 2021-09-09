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