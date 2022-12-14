# Data Minded Academy - Introduction to Git

## Exercise 7 - Stash and tags
In this exercise, you will have to create your Git pre-commit hook. This will involve knowledge from the Linux & Bash course. As always, feel free to Google your issues. The tasks are the following:

1. Open a terminal and position yourself in the root of this folder (`exercise_7`).
2. With the `ls -a` command, locate the folder where all the Git magic happens.
3. Have a look at what's in there. Particularly in the `hooks`` folder. What do you think it is?
4. Create a pre-commit hook that will format and lint your code with, respectively, `black` and `flake8`. To do so, make sure you install the packages in the `requirements.txt` file by running:
```
pip3 install -r requirements.txt
```
