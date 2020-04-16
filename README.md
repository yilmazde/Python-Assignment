# Data Analysis: BUGS

*Mind and Brain: Introduction to Python,
Winter Semester 2019/2020 Final programming assignment,
Author: Deniz Yilmaz*


### Project Description

This program is written to analyse a given data with 2 categorical predictor variables and a continuous outcome variable. Although I used the data obtained from the "Bugs" experiment (data provided under "The Bugs Experiment" section), other data can also be analysed using this program. In order to do so, it is sufficient to follow the specified guidelines in the program. Namely, you need to access that specific data and assign variable names that represent variables of the data in use. Specifics of the program is explained under "In This Program" section below.
I used Jupyter Notebook to write the program and the file is therefore an .ipynd file. If you choose only to view the project you can do so by clicking on the .ipynd file. If you wish to use the program interactively you may download the file and open it on Jupyter Notebook and modify the code as you like.

### The Bugs Experiment

The Bugs experiment is explained in the assignment guideline as follows: 

A somewhat silly psychology experiment conducted in 2013 measured subjects’ reactions to pictures of bugs. 
Independent raters had deemed the bugs to be either **disgusting or non-disgusting**, 
and either **frightening or non-frightening**. 
The subjects had to rate how much they **wanted to kill** each bug, on a scale from 1 to 10. 

That is to say:
There are 2 categorical Predictor Variables (PV): *Disgust, Fear* and a continuous Outcome Variable (OV): *KillRating*

More about the bugs experiment: 
https://doi.org/10.1016/j.chb.2013.01.024

**Obtain a csv file of the data from the experiment**:
https://raw.githubusercontent.com/luketudge/stats-tutorials/master/tutorials/data/bugs.csv 

### In This Program

I will display the Python program I wrote, with the help of Jupyter Notebook, which produces an analysis of the Bugs data. 
This program includes the following sections, each with a specific aim:

    0. First things first: 
       ◦ Importing the necessary modules
       ◦ Reading and printing the dataframe (DF).
       ◦ Assigning names to the predictor variables (PV1 & PV2) and the outcome variable (OV)

    1. Summary Statistics of Kill Ratings (Summary statistics of the kill ratings for each type of bug):
       (Bug Types: HighDisgustHighFear, HighDisgustLowFear, LowDisgustHighFear, LowDisgustLowFear)
        ◦ minimum
        ◦ maximum
        ◦ median
        ◦ mean
        ◦ Standard Deviation

    2. Lineer Model Results:
       The results of a linear model with kill rating as the outcome variable and the categories of bug as the predictor variables. Please        note that the linear equation needs to be specified by using appropriate variable names, depending on the dataframe in use.

    3. Graphic Representation:
       Boxplots with overlaid points showing the distribution of kill ratings for each category of bug. Again, please consider your              dataframe when specifying names to display with your plot.
       
    4. Testing:
       A test to see the assigned default values of PV1, PV2, and OV. These will only be printed if the program is run as the main module. 

### Source Information

I will indicate each source I have used for this program by putting "*Source:*", right above the related part throughout this notebook.

If no source had been indicated, related information can most likely be found on the GitHub page by Luke Tudge:
https://github.com/luketudge/introduction-to-programming/blob/b1010a12602bde5be5184e55190528c219ee7dac/content/data_analysis.ipynb

Source for learning Jupyter: 
https://www.youtube.com/watch?v=HW29067qVWk



