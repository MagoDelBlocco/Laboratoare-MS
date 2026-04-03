# Laboratoare MS
## Setup Laborator MS

The lab notebooks are organized in subfolders named `lab00`, `lab01`, ..., `lab13`. (Labs 00-09 are zero-padded for alphabetical ordering.)

### Option 1: Google Colab

Download the source file for the desired lab from its folder. For instance, for Lab 0:

    wget https://raw.githubusercontent.com/MagoDelBlocco/Laboratoare-MS/master/lab00/MS-lab00.ipynb

For other labs, replace `00` with the appropriate lab number (e.g., `lab05/MS-lab05.ipynb` for Lab 5, `lab09/MS-lab09.ipynb` for Lab 9). Labs 11, 12, and 13 are not zero-padded (`lab11/MS-lab11.ipynb`, `lab12/MS-lab12.ipynb`, `lab13/MS-lab13.ipynb`). Lab 9 also includes a data file `kc_house_data.csv`.

Open [Google Colab](https://colab.research.google.com/) in a web browser.

Select "Upload" and use the previously downloaded source.

### Option 2: Jupyter Lab - local

Download the [latest version of Python](https://www.python.org/downloads/) for your operating system (on Unix-based systems, you can use your package manager; on Windows, it's recommended to download from the Microsoft Store).

Install [pip](https://pip.pypa.io/en/stable/installation/), the Python package manager.

Install [Jupyter](https://jupyter.org/install).

Start the Jupyter Lab server using the command `python3 -m jupyterlab`. A new browser window will open with the application.

In the navigation menu on the left, navigate to the desired lab folder (e.g., `lab00/` for Lab 0) and double-click the notebook file.

### Option 3: VSCode - local

Clone or download the repository, then open the desired lab folder in VSCode. Open the notebook file; VSCode will prompt you to install necessary extensions.

## FAQ
Q: I keep trying to install `numpy` or `scipy`, but it says that I don't have it installed when I try to import.

A: Try to install it with `python3 -m pip install X` to make sure that you are installing the library for the appropriate python runtime.
