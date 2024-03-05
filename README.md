# Laboratoare MS
## Setup Laborator MS
### Option 1: Google Colab

Download the source file for each week (MS-labX.ipynb).
    
    wget https://raw.githubusercontent.com/MagoDelBlocco/Laboratoare-MS/master/MS-labX.ipynb

Open [Google Colab](https://colab.research.google.com/) in a web browser.

Select "Upload" and use the previously downloaded source.

### Option 2: Jupyter Lab - local

Download the [latest version of Python](https://www.python.org/downloads/) for your operating system (on Unix-based systems, you can use your package manager; on Windows, it's recommended to download from the Microsoft Store).

Install [pip](https://pip.pypa.io/en/stable/installation/), the Python package manager.

Install [Jupyter](https://jupyter.org/install).

Start the Jupyter Lab server using the command `python3 -m jupyterlab`. A new browser window will open with the application.

In the navigation menu on the left, find the previously downloaded source and double-click it.

### Option 3: VSCode - local
Just download the file and open it with VSCode. It will prompt you to install the necessary extensions.

## FAQ
Q: I keep trying to install `numpy` or `scipy`, but it says that I don't have it installed when I try to import.

A: Try to install it with `python3 -m pip install X` to make sure that you are installing the library for the appropriate python runtime.
