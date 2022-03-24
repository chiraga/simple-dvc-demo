create env

```bash
conda create -n wineq python=3.9 -y
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
download the data from 
https://drive.google.com/drive/folders/18zqQiCJVgF7uzXgfbIJ-04zgz1ItNfF5

git init

dvc init

dvc add data_given/winequality.csv

git add .

git commit -m "first commit"

create an empty repo on github remote with name simple-dvc-demo, do not give desc or gitignore or readme

git remote set-url origin https://chiraga@github.com/chiraga/simple-dvc-demo.git

git remote add origin https://github.com/chiraga/simple-dvc-demo.git

git branch -M main

git push -u origin main