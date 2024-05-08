# 01_Intro_to_ML
In this lab you will:
- Create your working environment (see below)
- Get used to work with notebooks (i.e., Jupyterlab)
- Get a refresher about python basics
- Learn how to use two powerful python packages for data science: NumPy and Pandas
- Create your first ML algorithm from scratch: K-means

## Prequisites
* [git](https://git-scm.com/downloads) installed on your computer
* [Python 3.10 or later](https://www.python.org/downloads/) installed on your computer 



## Setup of the working environment (only the first time, the first lab)
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

5. [Optional] Other modueles that you may want to install now are:
```
pip install numpy
pip install pandas
pip install matplotlib
pip install -U scikit-learn
```

6. Now, you car use this virtual environment in your  project on your preferred IDE (VS Code, Pycharm, etc.) or [Jupyter lab](https://jupyter.org/) (see the instructions below to launch Jupyter lab). Before doing so, we need to introduce our virtual environment to jupyterlab so that we can use it (*remember* to use this command inside of the virtual environment, after activating it).

```
python -m ipykernel install --user --name=venv_AML
```

Your working environment is ready!

## Installation of the project
1. If not done yet, clone this project in your *your_AML_main_folder*
```
git clone <url of the project to clone>
```

2. Open this project on your IDE (VS Code, Pycharm, etc.) or Jupyther lab (see below). Once loaded, be sure to use the interpreter in the virtual environment created above. See the instructions of your IDE.
   

## Running this project using Jupyter lab
If you want to run this project directly using Jupyter lab:

1. Open a terminal in the project folder and activate the virtual environment (e.g., called `venv_AML`) 
```
<path_to_your_venv>\venv_AML\Scripts\activate
```
on mac
```
source <path_to_your_venv>/venv_AML/bin/activate
```

2. Launch jupyterlab. In the terminal simply type:
```
jupyter lab
```
3. In jupyter lab select the kernel `venv_AML`

4. Have fun...

5. To deactivate the virtual environment

Windows:
```
.\venv_AML\Scripts\deactivate
```
Mac:
```
source deactivate
```
