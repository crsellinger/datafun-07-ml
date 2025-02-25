# datafun-07-ml-
Module 7: Machine Learning

## How to Install and Run Project
**Create virtual environment**
```shell
py -m venv .venv
```
**Activate virtual environment**
```shell
./.venv/Scripts/Activate
```
**Install Dependencies**
```shell
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt

py -m pip install -U spacy==3.5.3
py -m spacy download en_core_web_sm
```
**Running**

After activating virtual environment, use following command template to run in terminal. Outputs will be reflected in the database file (project.sqlite3).

```shell
py ./[script name]
```
To run in Jupyter notebook, click Kernel (top right) > Python environments > virtual environment. You can then run each cell (or all) in Jupyter notebook.
Icon in top right should look like the screenshot below:

