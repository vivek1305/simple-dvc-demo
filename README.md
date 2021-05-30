create env

```bash
conda create -n wineq python=3.7 -y
```

activate env
```bash
conda activate wineq
```

create a req file
```bash
pip install -r requirements.txt
```

https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

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
oneliner update for README.md
```bash
git add . && git commit -m "update README.md"
```
```bash
git remote add origin https://github.com/vivek1305/simple-dvc-demo.git
```
```bash
git branch -M main
```
```bash
git push origin main
```

tox command -
```bash
tox
```

for rebuliding -
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

build your own package commands -
```bash
python setup.py sdist bdist_wheel
```

create an artifact folder

mlflow server command -

mlflow server \
	--backend-store-uri sqlite:///mlflow.db \
	--default-artifact-root ./artifacts \
	--host 0.0.0.0 -p 1234