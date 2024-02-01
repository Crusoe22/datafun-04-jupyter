# datafun-04-jupyter
Project 4 repo for data analytics

## How to Install and Run the Project
Install and create a virtual environment to the local machine. Then I used the command (py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy) to downloand the necessary packages. These are frozen to requirements.txt.

### Follow these steps:

#### 1. Create Virtual Environment
    py -m venv .venv
    .venv\Scripts\Activate
    py -m pip install -r requirements.txt

#### 2. Add dependencies
    py -m pip install jupyterlab
    py -m pip install numpy
    py -m pip install pandas
    py -m pip install matplotlib 
    py -m pip install seaborn
    py -m pip install scipy


#### 3. Freeze dependencies
py -m pip freeze > requirements.txt


#### 4. Git add and commit
    git add .
    git commit -m "add .gitignore, cmds to readme"
    git push origin main