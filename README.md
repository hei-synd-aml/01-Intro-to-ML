# 01_Intro_to_ML
In this lab you will:
- Get used to work with notebooks (i.e., Jupyterlab)
- Get a refresher about python basics
- Learn how to use two powerful python packages for data science: NumPy and Pandas
- Create your first ML algorithm from scratch: K-means


## Installation and Setup of the working environment (only the first time, the first lab)
You have two options to setup your working environment:

1. **Option 1 (recommended)**: Use the provided `pyproject.toml` file to create a virtual environment with all the dependencies needed for this lab. Follow our tutorial [here](https://github.com/hei-synd-aml/lab-0-TutoUv) or follow the instructions provided in the official [uv documentation](https://docs.astral.sh/uv/guides/projects/#running-commands).
2. **Option 2**: Create a virtual environment and install the dependencies manually. *See the instructions below*.

### Option 2 (NOT recommended): Create a virtual environment and install the dependencies manually
Here we will create a virtual environment (e.g., called `venv_AML`) that you will use for all your labs on this course. 

1. Create or select a folder where the dependencies will be installed. We suggest that you select a folder above all of your (future) labs folders.  
```
+----your_AML_main_folder
|     +---venv_AML
|     +---lab_01
|     +---lab_02
...   ...
```

2. Using a terminal, use the following commands to create your virtual environment:
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
source ./venv_AML/bin/activate
```
4. To use the virtual env., update pip and install the following modules:
```
python -m pip install --upgrade pip
pip install ipykernel
pip install jupyter
```

5. [Optional] Other modules that you may want to install now are:
```bash
pip install ipykernel
pip install -U scikit-learn
pip install numpy
pip install pandas
pip install matplotlib
pip install jupyter-black
```

6. Now, you can use this virtual environment in your project on your preferred IDE (VS Code, Pycharm, etc.). Before doing so, we need to introduce our virtual environment to jupyter so that we can use it. *Remember* to use this command inside of the virtual environment, after activating it. Some IDEs will automatically manage this task for you. If not execute: 

```
python -m ipykernel install --user --name=venv_AML
```

Your working environment is ready!
