# AI-Project-1

Our project aim is to answer if adult children are not doing as well as earlier generations.  Using sourced data and adjusting for inflation where necessary.

## Table of Contents

- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Install Python](#install-python)
  - [Install Jupyter Notebook](#install-jupyter-notebook)
  - [Install Libraries](#install-libraries)
- [Usage](#usage)
  - [Running Jupyter Notebook](#running-jupyter-notebook)
  

## Installation

- [Python Documentation] (<https://docs.python.org/>)
- [Jupyter Notebook Documentation] (<https://jupyter-notebook.readthedocs.io/>)
- [Matplotlib Documentation] (<https://matplotlib.org/stable/index.html>)
- [SciPy and NumPy Documentation] (<https://docs.scipy.org/doc/>)
- [Google Colab] (<https://colab.research.google.com>)

### Prerequisites

- A computer running Windows, macOS, or Linux
- Administrator privileges on the computer

### Install Python

1. Download the latest version of Python from the official [Python website](https://www.python.org/downloads/).
2. Run the installer and follow the instructions. Make sure to check the option to add Python to your PATH.

To verify the installation, open a terminal or command prompt and run:

python --version

## Install Jupyter Notebook

pip install notebook

## Install Libraries

pip install matplotlib scipy numpy

## Clone the repository

- Open a Terminal window and use `cd` commands to navigate to the directory where you would like to save your repository.

- Use the `git clone` command and the link you copied previously to clone the repository in the location you selected.

- Run all .ipynb files, except generation_prophet_compare_final.ipynb, using jupyter notebook, an anaconda dev setup may be preferable

- Run generation_prophet_compare_final.ipynb in a google colab workspace.  Upload the dfa-generation-levels-detail-cleanedup.csv found in the resources-jc folder when prompted.

## Running Jupyter Notebook

jupyter notebook

## Sources

- [combining multiple data frames](https://stackoverflow.com/questions/53877687/how-can-i-concat-multiple-dataframes-in-python)
- [Federal Reserve Data](https://www.federalreserve.gov/releases/z1/dataviz/dfa/compare/chart/#quarter:137;series:Assets;demographic:generation;population:all;units:levels)
- [charting tools](https://www.shanelynn.ie/bar-plots-in-python-using-pandas-dataframes/)
- [student loan stats](https://educationdata.org/student-loan-debt-statistics)
- [stacked to full bar chart](https://www.shanelynn.ie/bar-plots-in-python-using-pandas-dataframes/)
- [secondary axis](https://stackoverflow.com/questions/46063379/pandas-secondary-axis)
- [Historical Median Income](https://fred.stlouisfed.org/series/MEHOINUSA672N)
- [Historical Median rent cost](https://ipropertymanagement.com/research/average-rent-by-year)
- [Percentage format](https://saturncloud.io/blog/how-to-format-certain-floating-dataframe-columns-into-percentage-in-pandas/)
- [Average Net Worth per Generation](https://www.self.inc/info/generational-wealth-gap/)

## Findings

- Today's 40-year-olds own 25% less wealth compared to older generations when they were the same age.
- Baby boomers owned 25% more real estate than Generation X at the same age.
- Baby boomers are collectively 8 times wealthier than millennials.
- Millennials are 22.4% behind Generation X in terms of wealth accumulated.
- According to an analysis of Federal Reserve data, the average baby boomer now has a median net worth of $206,700. However, the average net worth of baby boomers is considerably higher, at a whopping $1.2 million showing how significantly the top earners skew the average higher.
- The inability of lower earning and younger millennials and likely gen z to save for the american dream, owning their own housing, due to an increasing percent of income going to rent and home prices + major assets like equities will likley make it harder for more and more household formation and ability to acquire their parents level of net wealth.
- Inheritence and relying on parents for help will likely play into more haves and have nots.
