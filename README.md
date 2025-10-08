# Python for Data Science – NMFP451

Course info and materials.

Practicals: Ondřej Týbl, Filip Bočinec ([surname]@karlin.mff.cuni.cz)

Time: Monday 12:20

Room: K4

## Plan
| Date       | Topic                          | Homework Assignment | Homework Deadline[^1] | Lecturer |
|------------|--------------------------------|---------------------|------------------|----------|
| 29.09.2025 | introduction                   | [click](https://github.com/ondratybl/python-for-data-science/blob/main/assignment1.ipynb)              | 15.10.2025           | Filip   |
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

After each deadline, we check your GitHub repositories and evaluate your solutions as `passed`, `revision` or `failed`. You need all the solutions to be marked as `passed` by `the end of January 2026` to obtain the course credits. If marked as `revision`, you can resubmit your improved solution to obtain `passed` (no submissions after `the end of January 2026`). Your results (under your UKČO) can be found [here](https://github.com/ondratybl/python-for-data-science/blob/main/HW_results.md).

## Use of Large Language Models

Large Language Models (LLMs) such as ChatGPT, DeepSeek, or other AI assistants can be powerful tools to support your learning and coding. We do not prohibit their use, but we expect you to use them wisely and responsibly. Please follow these guidelines:

- **Understand Before Using:** Always make sure you understand the answer or code snippet provided by an LLM. Do not copy-paste blindly; LLMs may produce errors or code that is not optimized.

- **Use as a Learning Aid, Not a Shortcut:** LLMs are helpful for explanations, examples, and clarifications. Try to solve exercises yourself first; then, if needed, consult an LLM for hints or guidance.

- **Verify and Test Everything:** Always verify the correctness of code or explanations given by an LLM. Run code locally and check outputs. Make sure it matches the theory and your understanding.

- **Develop Critical Thinking:** Use LLM outputs as a starting point, not a final answer. Compare multiple sources and reasoning to strengthen your understanding.

- **Privacy and Safety:** Avoid sharing sensitive personal data or credentials with LLMs.

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

# Setup Instructions

### 1) Install PyCharm

- Download the installer [here](https://www.jetbrains.com/pycharm/download/?section=mac).
- Install PyCharm using default options.

---

### 2) Install Git

- **Windows**  
  [Download Git for Windows](https://git-scm.com/download/win) (use the *64-bit Git for Windows Setup*).  
  Install with the recommended (default) settings.  
  Verify installation by opening **Command Prompt** and typing:  
  ```bash
  git --version
  ```

- **macOS**  
  Install Xcode Command Line Tools (which include Git) by running:  
  ```bash
  xcode-select --install
  ```  
  Verify installation by typing:  
  ```bash
  git --version
  ```

---

### 3) Create a GitHub Account

- Go to [GitHub](https://github.com) and create an account.
- Fork the course repository by clicking **Fork** here: [python-for-data-science](https://github.com/ondratybl/python-for-data-science).  
  (We strongly recommend keeping the default repository name.)
- A fork enables you to commit your own changes in a separate copy of the repository.

---

### 4) Create a Project in PyCharm

- (Windows) Select **Clone Repository**.
- (Mac) Select **Get from VCS**.
- Enter the URL of your forked repository:  
  ```
  https://github.com/[your-username]/python-for-data-science
  ```
- Select **Clone**.

---

### 5) Create a Python Environment

- (Mac) In the bottom-right corner of PyCharm, click on `<No Interpreter>`, select **Add New Interpreter → Add Local Interpreter**. Create a new **virtual environment** with Python 3.11 (if not present, PyCharm will download it). Open the Terminal in PyCharm (icon in the bottom-left corner). Make sure your command line starts with `(.venv)` → this confirms the virtual environment is active. Install all required packages:
  ```bash
  pip install -r requirements.txt
  ```
- (Windows) After project is created, **Creating Virtual Environment** window should pop up (if not, follow Mac instructions). As base interpreter, choose Python 3.11 and click **OK**
- A blue progress bar will appear at the bottom of PyCharm when processes such as package installation are running. Please wait until it completes.
- If you need additional packages later, install them via:
  ```bash
  pip install [package]
  ```

---

### 6) Submit a Test Homework Solution

- Open `assignment1.ipynb` in PyCharm
- Click **Run** to verify everything works.
- Add a new cell that prints your GitHub username.
- Submit your solution with **Git → Commit → Commit and Push**.  
  - Enter a commit message.  
  - Click **Commit and Push**.
  - Now GitHub wants to authenticate you. Select authentitacion via **Token**, now a new window where you should enter your token will appear. To create this token, go to GitHub website select your account icon in the top-right –> **Settings** –> **Developer Settings** –> **Personal access tokens** –> **Tokens (classic)** –> **Generate new token** –> add some description, validity deadline, select **repo** and **Generate token**. The token will appear and paste it in your PyCharm.
- Verify your changes at:  
  ```
  https://github.com/[your-username]/python-for-data-science
  ```
- Tell us your name and GitHub username.  
  All future homework solutions will be submitted the same way.

---

### 7) 🎉 Congratulations!
You are ready to start working on the course!


### FAQ

1) Problem: When creating virtual environment, Pycharm does not provide any python versions. Solution: Completely erase the project including the folder in PycharmProjects and create it from scratch. If does not help, install desired python version yourself.
