# Machine Learing and Statistics
# Tasks 2020

### Lecturer: Ian McLoughlin

### Student: Damien Connolly
### G00340321
<br/>

***********************************************************************************************************************************


#### OVERVIEW OF TASKS
Sqrt2 - Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library1 or otherwise. You should research the task first and include references and a description of your algorithm.

Chi-squared - The Chi-squared test for independence is a statistical hypothesis test like a t-test. It is used to analyse whether two categorical variables are independent. The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6. Use scipy.stats to verify this value and calculate the associated p value. You should include a short note with references justifying your analysis in a markdown cell.

Standard deviation - The standard deviation of an array of numbers x is calculated using numpy as np.sqrt (np.sum((x - np.mean(x))**2)/len(x)). However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 rather than len(x). Research these Excel functions, writing a note in a Markdown cell about the difference between them. Then use numpy to perform a simulation
demonstrating that the STDEV.S calculation is a better estimate for the standard deviation of a population when performed on a sample. Note that part of this task is to figure out the terminology in the previous sentence.

K-nearest neighbours - Use scikit-learn to apply k Nearest Neighbours clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris.



#### PACKAGES USED IN THIS PROJECT
The following packages were used to run analysis for this project.

Python https://www.python.org/downloads/

Anaconda https://www.anaconda.com/distribution/ - is the easiest way to perfrom Python data science machine learning on Linux, Windows and Mac OS.

iPython https://ipython.org/ - it an interactive command-line terminal for Python.

Numpy http://www.numpy.org/ - is the fundamental package for scientific computing within Python.

Jupyter Notebook https://jupyter.org/ - is an open-source web application that allows the creation and sharing of documents that contains live code, equations, visualisations and narriative text

pandas https://pandas.pydata.org/

seaborn https://seaborn.pydata.org/

scipy.stats https://docs.scipy.org/doc/scipy/reference/stats.html

matplotlib.pylab https://matplotlib.org/

scikit-learn https://scikit-learn.org/stable/
