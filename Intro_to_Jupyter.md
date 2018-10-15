# Intro-to-Jupyter
##### Jupyter Notebooks are a powerful way to write and iterate on your Python code for data analysis. [Jupyter](http://jupyter.org/index.html) isn’t a different programming language, it’s just a set of computer programs for working with the Python language. Having said that, having python is a prequisite for working with Jupyter Notebook.
## To istall Jupyter
##### * install [Anaconda](https://www.anaconda.com/download/) which is a free bundled installer of Python together with many other useful tools (including Jupyter Notebook and other libraries like matplotlib) 
##### * if you already have python installed and feel confortable with it, you can install Jupyter (plus matplotlib) using Python's package manager ‘pip’ as follows:
##### for Python3
`python3 -m pip install --upgrade pip
python3 -m pip install jupyter`
##### for python2.7
`python -m pip install --upgrade pip`
`python -m pip install jupyter`
##### *Note:* Python 2 and Python 3 have some minor incompatible differences in language syntax. The programs shown in this workshop are designed to work with both, but if you find some code that doesn’t work (but perhaps works on your neighbour’s computer) then this may be why.

## Running Jupyter
##### If you downloaded Anaconda: 
##### * on Windows, launch Jupyter Notebook under Anaconda from the start menu
##### * on Linux/OS X, in the terminal, use 'cd' to navigate to the directory where you store your Python and notebook document files. Then run:
`jupyter notebook`

##### You should see the notebook open in your default browser. If it doesn’t open, you can copy-paste the “http” address from the output and paste it into your browser.
##### You interact with Jupyter Notebook using your web browser. The Notebook program creates a “web server” locally on your computer that you then connect to. 
##### *Note:* Even though you’re interacting with Jupyter Notebook using your browser, Notebook is running right there on your computer in that window. Only you have access to it.
