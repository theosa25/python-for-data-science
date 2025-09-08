# Python for Data Science – NMFP451

Course info and materials.

Practicals: Ondřej Týbl, Filip Bočinec ([surname]@karlin.mff.cuni.cz)

Time: Monday 12:20

Room: K4

## Plan
| Date       | Topic                          | Homework Assignment | Homework Deadline[^1] | Lecturer |
|------------|--------------------------------|---------------------|------------------|----------|
| 29.09.2025 | introduction                   | [click](https://github.com/ondratybl/python-for-data-science/blob/main/assignment1.ipynb)              | 20.10.2025           | Filip   |
| 13.10.2025 | numpy                          | [TODO]             | 20.10.2025           | Filip   |
| 27.10.2025 | pandas                         | [TODO]              | 03.11.2025           | Ondřej   |
| 10.11.2025 | sql                            | [TODO]              | 17.11.2025           | Ondřej   |
| 24.11.2025 | matplotlib                     | [TODO]              | 01.12.2025           | Ondřej   |
| 08.12.2025 | scikit-learn                   | [TODO]              | 15.12.2025           | Filip   |
| 05.01.2026 | Object-oriented programming    | [TODO]              | 12.01.2026           | Ondřej   |

[^1]: All homework deadlines are due at **23:59** on the specified date.

## Materials

- [w3schools](https://www.w3schools.com/python/)
- [MIT](https://ocw.mit.edu/courses/6-100l-introduction-to-cs-and-programming-using-python-fall-2022/)

## Requirements

Several homework assignments will be given. You are required to submit a solution for each assignment by the respective deadline. Your code will be evaluated based on readability, efficiency, correctness, and whether it runs successfully.

After each deadline, we check your GitHub repositories and evaluate your solutions as `passed`, `revision` or `failed`. You need all the solutions to be marked as `passed` by `the end of January 2026` to obtain the course credits. If marked as `revision`, you can resubmit your improved solution to obtain `passed` (no submissions after `the end of January 2026`).

## Use of Large Language Models

[TODO]

## Setting up everything

In our course, we will learn how to use a whole bunch of tools and technologies that form the foundation of data science.

| Category                     | Solution             | Description                                                                |
|------------------------------|---------------------|-----------------------------------------------------------------------------|
| Programming Language         | Python              | The language used to write and execute code.                                | 
| Integrated Development Environment (IDE)      | PyCharm             | Editor for writing, debugging, and managing projects (+ many more).                |
| Virtual Environment          | venv                | An isolated environment to manage project-specific package dependencies.            |
| Script / Notebook            | Jupyter Notebook    | An interactive file format/environment for running and documenting code.    |
| Version Control System (VCS) | Git                 | Tracks code changes and manages project history.                            |
| VCS Hosting Platform         | GitHub              | Cloud-based platform for hosting and collaborating on Git repositories.     |

Below, a detailed instructions on how to set everything up is provided.

### 1) Install PyCharm

- Go to [PyCharm Student License Form](https://www.jetbrains.com/shop/eform/students)
- Fill in the form to get the license, you can use your @cuni.cz email or ISIC
- Download and install

### 2) Install git

- (Windows) [Download](https://git-scm.com/downloads/win) the installer (presumably, you need Git for Windows/x64 Setup), use recommended and defult settings to install it, verify installation by typing 'git --version' in your Command Prompt
- (Mac) Install Xcode, verify installation by typing 'git --version' in your Terminal

### 3) Create GitHub account

- Go to [GitHub](https://www.github.com)
- Create your account
- Create a course repository fork by navigating to 'fork' [here](https://github.com/ondratybl/python-for-data-science), we strongly encourage you to use keep the default repository name
- A fork enables you to commit your own changes into your separate repository

#### 3) Create project

- Open Pycharm
- Select 'Get from VCS' to connect to your repository, use url https://github.com/[username]/python-for-data-science and select `Clone`

### 4) Create python environment
- In the bottom right, click on the <No Interpreter>, select "Add New Interpreter" -> "Add Local Interpreter"
- Create a new virtual environment with Python 3.11 (if not present, it will be downloaded)
- open Terminal in PyCharm (one of the icons in the left-down corner)
- make sure there is `(.venv)` at the beginning of your command line, denoting you are now in the activated virtual environment, that you created in the previous steps
- install all necessary packages by typing `pip install -r requirements.txt`
- whenever you find out that you want to add some package, just open the Terminal in pycharm and type `pip install [package]`

### 5) Submit a test homework solution
- navigate to `assignment1.ipyng` in the left and double-click
- select 'run' to test that everything works properly
- add a new cell that will print your username on GitHub
- submit the solution via a git push, just select <Git> in the top panel –> <Commit> –> insert some commit message –> Commit and Push
- check https://github.com/[username]/python-for-data-science to see the code change
- tell us your name and GitHub username, all the following homework solutions will be submitted using this way

### 6) Congratulations!

You are now ready to create your code.

[TODO]: logging, tqdm, try/except, seaborn, pep 8, comments
