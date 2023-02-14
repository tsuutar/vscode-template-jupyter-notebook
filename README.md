# VSCode用Jupyter Notebookテンプレート

## 環境の作成

```
$ python -m venv .venv
$ .venv\Scripts\Activate.bat
$ .venv\Scripts\python.exe -m pip install --upgrade pip
$ pip install -r requirements.txt
```

## Jupyter Notebook 起動

```
$ jupyter notebook
```

## 環境情報の保存

```
$ pip freeze > requirements.txt
```
