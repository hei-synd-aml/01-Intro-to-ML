# 01_Intro_to_ML
In this classe you will:
- Get a refresh about python basics
- Learn how to use two powerful packages for data science: NumPy and Pandas
- Create your first ML programs from scratch
- Getting started with Expoloratory Data Analyis

## Prequisites
Python > 3.10 installed on your machine 

## Installation of this project (only the first time)
1. Copy or Clone this project
2. [Optional] Create a virtual environment (e.g., called `venv_AML`)
```
py -m venv venv_AML
```
3. Activate the virtual environment

Windows:
```
.\venv_AML\Scripts\activate
```
Mac:
```
source venv_AML/bin/activate
```
4. Tu use the virtual env in jupyter lab you need to install (if not in requirements.txt):
```
pip install ipykernel
```
5. Now, before running Jupyterlab, we want to introduce our virtual environment to jupyterlab so that we can use it(*remember* to use this command inside of virtual environment)

```
python -m ipykernel install --user --name=venv_AML
```

6. Update pip and install the requirements (if any)
```
python -m pip install --upgrade pip
pip install -r requirements.txt
```
7. Deactivate the virtual environment

Windows:
```
.\venv_AML\Scripts\deactivate
```
Mac:
```
source deactivate
```

DONE: the project is ready to be executed!
   

## Running this project 

1. Activate the virtual environment (e.g., called `venv_AML`) 
```
.\venv_AML\Scripts\activate
```
on mac
```
source venv_AML/bin/activate
```

2. Launch jupyterlab
```
jupyter lab
```
3. In jupyter lab select the kernel `venv_AML`
4. Have fun
5. Deactivate the virtual environment

Windows:
```
.\venv_AML\Scripts\deactivate
```
Mac:
```
source deactivate
```
