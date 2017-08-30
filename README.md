# "Automated Inference of Chemical Discriminants of Biological Activity" Code Repository


Complimentary dataset and code for the chapter

**"Automated Inference of Chemical Discriminants of Biological Activity"**

in the book *"Computational drug discovery and design"** (Methods in Molecular Biology, Springer Protocols).

Authors:  
[Sebastian Raschka](https://sebastianraschka.com), [Anne M. Scott](https://msu.edu/~liweim/index.htm), [Mar Huertas](http://www.bio.txstate.edu/about/Faculty---Staff/faculty/Huertas--Mar.html), [Weiming Li](https://msu.edu/~liweim/index.htm), and [Leslie A. Kuhn](http://www.kuhnlab.bmb.msu.edu)


---
---


## Requirements

#### Python Interpreter

To run the code examples, a recent version of Python is required (3.5 or 
newer) is required; Python 3.6 is recommended. 
You can https://www.python.org/downloads/. 

#### Python Libraries

The following list specifies the Python libraries used in this chapter, the recommended version number, and a short description of their use:
-   NumPy version 1.13.0 or newer (http://www.numpy.org); numerical array library
-   SciPy version 0.19.0 or newer (https://www.scipy.org); advanced functions for scientific computing
-   Pandas version 0.20.1 or newer (http://pandas.pydata.org); handling of CSV files and working with data frames
-   Matplotlib version 2.0.2 or newer (https://matplotlib.org); 2D plotting 
-   Scikit-learn version 0.18.1 or newer (http://scikit-learn.org/stable/); algorithms for machine learning 
-   MLxtend version 0.7.0 or newer (http://rasbt.github.io/mlxtend/); sequential feature selection algorithms

The scientific computing libraries listed above can be installed using Python's in-built [Pip](https://pypi.python.org/pypi/pip) module  by executing the following line of code directly from a macOS/Unix, Linux, or Windows MS-DOS terminal command line:

    pip install numpy scipy pandas matplotlib scikit-learn pydotplus mlxtend

If you encounter problems with version incompatibilities, you can specify the package versions explicitly, as shown in the following terminal command example:

    pip install numpy==1.13.0 scipy==0.19.0 pandas==0.20.1 matplotlib==2.0.2 scikit-learn==0.18.1 pydotplus==2.0.2 mlxtend==0.7.0

#### Graph Visualization Software

To visualize the decision trees later in this chapter, an installation of GraphViz is needed. The GraphViz downloader is freely available at http://www.graphviz.org with the installation and setup instructions.


#### Jupyter Notebook

To open and execute the code in the file [code/dkpes_fgroup_analysis.ipynb](code/dkpes_fgroup_analysis.ipynb) locally, Jupyter Notebook for Python is required. For more information on installing Jupyter Notebook, please visit http://jupyter.readthedocs.io/en/latest/install.html.

Alternatively, if you don't want to install Jupyter Notebook, you can view the code in your browser by clicking on the [code/dkpes_fgroup_analysis.ipynb](code/dkpes_fgroup_analysis.ipynb) file in this GitHub repository.

