# guided-data-csv
A guided tutorial for analyzing data in CSV files using Jupyter notebooks.

# Introduction

# Downloading and Installing Anaconda
Begin by navigating to the [Individual Edition](https://www.anaconda.com/products/individual) of Anaconda. Click the Download button. Open the downloaded file. During the installation process, use the option to "Install for: Just Me." Use default settings during installation.

After installation, search your PC for Anaconda Navigator. Add to your Desktop. Launch the program.

When you launch Anaconda, you will see many "apps" available for launch, including Datalore, JupyterLab, Jupyter Notebooks, VS Code, and others.

We will launch a "Notebook." Find the Notebook app, and click on Launch. Open it using Google Chrome. It is helpful to save these Jupyter Notebooks within an organized set of folders on your computer.

# Jupyter Notebook Basics
Click the '+' button to create a new cell.
Shift + Enter runs a cell.
Enter creates a new line within a cell.
Cells must be executed sequentially; for example, necessary packages (like NumPy or Pandas) must be imported _before_ they can be used.
While in a cell, type Esc+M at the same time to change the cell to a MARKDOWN cell. This enables you to write text in the cell.
Use # to create comments in a Python3 cell. It is good practice to explain what each of your lines of code is doing.

# Commonly Used Libraries, and their Documentation
To install or update Pandas, NumPy, or any other library, open up a Cmd.exe from the Anaconda Navigator. Find their Anaconda.org page (e.g. https://anaconda.org/anaconda/pandas) and follow the instructions there.

Pandas Documentation: https://pandas.pydata.org/docs/user_guide/index.html (Use the search bar in the top left to find what you're looking for. e.g. "read_csv" will provide Documentation links to learn more about pandas.read_csv).

NumPy Documentation: https://numpy.org/doc/stable/ (Uses a similar search bar).

Seaborn Documentation: https://seaborn.pydata.org/api.html (A list of the various plots you can make in Seaborn, along with examples).

# Commonly Used Functions
_Pandas_:
[pd.read_csv](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html?highlight=read_csv)
[pd_read_excel](https://pandas.pydata.org/docs/reference/api/pandas.read_excel.html?highlight=read_excel)
[.head()](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.head.html)
[.info()](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.info.html?highlight=info#pandas.DataFrame.info)
[pd.to_csv()](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html?highlight=to_csv#pandas.DataFrame.to_csv)
[pd.to_excel()](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_excel.html?highlight=to_excel#pandas.DataFrame.to_excel)
