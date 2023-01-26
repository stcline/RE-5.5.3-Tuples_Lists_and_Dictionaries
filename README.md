# :robot: Tuples, Lists and Dictionaries

## 🤓 Overview and learning outcomes 

In this lab we will begin to explore three new data types in Python.  These three may be used to expand the capabilities of our code significantly. If you need to store a long list of information which may or may not need to change or need to be indexed, these concepts will be very useful.

The goal of this lab assignment is to introduce you to these data types and how to use them in Python scripts. 🚀

#### Over the course of this lab you will do a number of things:
1. Create lists, tuples and dictionaries using Python syntax.
2. Utilize some of the methods in Python to modify existing examples of these three data types.
3. Use correct syntax to find and request values from various parts of your data.

## 💻 Terms to know
- lists
- tuples
- dictionaries
- arrays
- `.append()`

## 📝 Next steps
1. Complete the work in the notebook here (5_5_3_Tuples,_Lists_and_Dictionaries.ipynb) using the CoLab interface.
2. Using GIT, add the repo to your raspberry pi.
3. Using NANO and the terminal in your pi, create a new text file called "observations.txt" and write what you learned in this lab.
4. Using NANO and the terminal in your pi, create a three new scripts (name them whatever you like) which do the following (You will use the file "english_premier_clubs.csv" for all of these scripts):
    - Create a tuple variable called "teams" which contains the names of all of the clubs in the file and prints the length (number of teams) of the tuple automatically.
    - Create a list variable called "eng_teams" which contains the names of the teams in the file and allows the user of the script to add a new team to the list if they choose (use the `.append()` method along with the `input()` function).
    - Create a dictionary using the data contained in the file with the header row of the file as the keys and the other data as the values.
6. Add, commit and push your local branch to the main repo on GitHub.

***SPECIAL NOTE: While you may do this the long way and solve the problem, consider using the `pandas` module to make things easier.***

## 📚  Resources 
[Think Python Textbook](https://greenteapress.com/wp/think-python-2e/)

[Raspberry Pi Foundation - Getting Started with Git](https://projects.raspberrypi.org/en/projects/getting-started-with-git)
