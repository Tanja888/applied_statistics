# Applied Statistics 

## Repository Contents
The repository contains two Jupyter notebooks: `project.ipynb` and `tasks.ipynb` that include Python code in order to perform statistical analysis. 
The covered topics include:

  * Using `numpy`, `math`, `itertools`, `random` Python libraries to gain insight into statistical concepts of permutations and combinations
  * Test data normality using `numpy.random.normal()`  and Shapiro-Wilk test 
  * Compare two sets of data and their means by performing a t-test using `scipy` library
  * Understand how to perform ANOVA statistical test to compare more than two sets of values using `scipy`
  * Gain insight into concept of statistical errors by using an example of the Type II error while performing ANOVA test 
  * Visualise the outcomes of performed analysis with `matplotlib` and `seaborn`

## Run the code
This notebook can be run in two ways:
1.	On the local machine using [Visual Studio Code](https://code.visualstudio.com/) and [Anaconda](https://www.anaconda.com/download/success)
2.	Online using [Github Codespaces](https://github.com/codespaces)   

### 1. Run the notebook locally using Visual Studio Code and Anaconda
1. Clone the repository:
``` bash
git clone https://github.com/Tanja888/applied_statistics    
cd applied_statistics
```

2. Set up a virtual environment using Anaconda:
```bash
conda create -n sklearn-env python=3.9
conda activate sklearn-env
pip install notebook scikit-learn
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Launch Visual Studio Code:
- Open the repository folder in VS Code
- Install the Python extension if prompted
- Select the `sklearn-env` environment as your interpreter 

5. Run the Jupyter notebook:
- Open the notebook file `notebook.ipynb` in VS Code
- Use the integrated Jupyter environment to run cells interactively

### 2. Run the notebooks using GitHub Codespaces 
1. Click on the green “Code” button at the top of this repository page
2. Select “Open with Codespaces”
3. GitHub will automatically create and launch a Codespace
4. Open the notebook `notebook.ipynb` and run it directly in the browser

![probability comic](img/rabbit_comic.jpg)     

