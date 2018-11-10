# Probability distributions
Calculate and visualize Binomial and Gaussian distributions.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Sample Code](#sample)


## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the libraries preinstalled in Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*. Following are the libraries used in this project.

1. math
2. matplotlib

## Project Motivation<a name="motivation"></a>

For this project, I was interested in calculating and visualizing Binomial and Gaussian distributions.

## File Descriptions <a name="files"></a>

* general_distributions.py: Generic distribution class for calculating and visualizing a probability distribution.
* guassian_distributions.py: Gaussian distribution class for calculating and visualizing a Gaussian distribution.
* binomial_distributions.py: Binomial distribution class for calculating and visualizing a Binomial distribution.


## Sample Code<a name="sample"></a>

* Using Binomial distribution class

    ```
    binomial_object = Binomial()
    binomial_object.read_data_file("filename.txt")
    binomial_object.replace_stats_with_data()
    binomial_object.plot_bar_pdf()
    ```

* Using Gaussian distribution class

    ```
    guassian_object = Guassian()
    guassian_object.read_data_file("filename.txt")
    guassian_object.plot_histogram()
    guassian_object.plot_histogram_pdf()
    ```
