# profiler
[![python virtual environment](https://img.shields.io/badge/python_venv-3.12.3--1ubuntu0.13-green?logo=ubuntu&logoColor=orange)](#)
[![python version](https://img.shields.io/badge/python-3.12.3-blue?logo=python&logoColor=white)](#)
[![pip version](https://img.shields.io/badge/pip-24.0%20(python%203.12)-orange)](#)
[![jupyter version](https://img.shields.io/badge/jupyter-1.1.1-purple?logo=jupyter&logoColor=white&labelColor=yellow)](#)
[![wordcloud version](https://img.shields.io/badge/wordcloud-1.9.6-pink?labelColor=black)](#)

A wordcloud project for creating a profile.

#### Installing & creating virtual environment
- The project is build on top of Python's virtual environment in Ubuntu 24.04. Install depencies
  ```bash
  apt install python3.12-venv
  ```
- Create environment named vPy3 (virtual python for version 3)
  ```bash
  python3 -m venv vPy3
  ```

#### Activating virtual environment
activate virtual environment
```bash
source vPy3/bin/activate
```

#### Pre-checks
  - Python version and path
    ```bash
    python --version        # output: Python 3.12.3
    python3 --version       # output: Python 3.12.3

    which python            # output: <PROJECT_ROOT>/vPy3/bin/python
    which python3           # output: <PROJECT_ROOT>/vPy3/bin/python3
    ```
  - Pip version and path
    ```bash
    pip --version           # output: pip 24.0 from <PROJECT_ROOT>/vPy3/lib/python3.12/site-packages/pip (python 3.12)
    pip3 --version          # output: pip 24.0 from <PROJECT_ROOT>/vPy3/lib/python3.12/site-packages/pip (python 3.12)

    which pip               # output: <PROJECT_ROOT>/vPy3/bin/pip
    which pip3              # output: <PROJECT_ROOT>/vPy3/bin/pip3
    ```

#### Installing python's libs
Install `jupyter` and `wordcloud` once the virtual environment is [activated](#activating-virtual-environment)
```bash
cd profiler
pip install -r requirements.txt
```

#### How to run
Once the [dependencies](#installing-pythons-libs) are installed, run --
```
jupyter notebook
```
The command will run the project and open it in a browser. Open the developer profile and execute the project. 
