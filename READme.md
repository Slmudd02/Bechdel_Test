# Bechdel Test
### By Shala Mudd

![photo](https://variety.com/wp-content/uploads/2022/11/MCDDEWE_FE012.jpg?w=681&h=383&crop=1&resize=681%2C383)

## About

The Bechdel test was created to show how women are being pretrayed in a sexist way on film. In order to pass the test the films must contain three things:
 - Two lead female characters that the audience knows the name of 
 - Characters have to talk to each other
 - Must talk about something other than men

I have two datasets that I got from kaggle.com. The first are the top grossing movies of all time. The second are top grossing movies that passed or failed the Bechdel test. I mereged these two datasets together using python. 

## Source 
Kaggle.com

## How To Run This Program 
First clone my repo.

Then, create a vritual enviornment. 
In order to create a conda enviorment like I did you must have Anaconda installed on your computer. In the Anaconda prompt do the folowing code:
```python
conda --name venv_name python
```

Instead of "venv_name" put the name of the new virtual enviornment. Once it is created run the following code:
```
conda install jupyter 
```
```
conda install pandas
```
```
conda install matplotlib
```
```
conda install numpy
```
Then open Bechdel_test_project-checkpoint.ipynb file thats in my repo.

## Code Louisville Requirements Met
- Feature 1:
    - Read two data files
- Feature 2:
    - Clean data and perform a pandas merge with two data sets, then calculate some new values based on the new data set.
- Feature 3:
    - Make 3 matplotlib visualizations to display data.
- Feature 4:
    - Utilize a virtual environment and include instructions in the README on how the user should set one up
