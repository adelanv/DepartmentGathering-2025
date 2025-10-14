# Workshop: Multi-Agent LLMs with AutoGen for Digital Twins

## Setup 

### How to run?

#### Run on local machine (We follow this in this workshop!)

**Required**: Docker Desktop, VSCode (Or another Jupyter Notebook-friendly editor), Ollama (Optional), Git (Optional)

1) Clone the GitHub repository on your computer from following link:

```
git clone https://github.com/adelanv/DepartmentGathering-2025.git
```

2) Make sure Python >3.10 is installed on your machine, and is on your PATH
   ```https://realpython.com/add-python-to-path/```
   

3) Create a virtual environment:
    3.1) Using pip
   ```bash
    python3 -m venv .venv
   ```
    # For linux
   ```
   source .venv/bin/activate
   ```
    # On windows the activate script is located under the ./venv/Scripts/ folder, so with powershell:
    ```
   .\.venv\Scripts\activate
    ```
    # Or with git bash if installed
    ```
   source ./.venv/Scripts/activate
    ```
4) Install Docker Desktop on your computer, following the link: https://www.docker.com/%20products/docker-desktop/ then run Docker Desktop.

5) Open a terminal, navigate to the repository directory where the *docker-compose.yml* file is located and run the following command:

```
docker-compose up -d
```
6) Run the code blocks in an editor of your choice:

    5.1) [Visual Studio Code](https://code.visualstudio.com/) (Recommended)
        Open the project folder and set the virtual environment as the default interpreter.

    5.2) If Jupyter Lab is installed

       ```bash
        jupyter lab

       ```
    or if you need to specify python version (for example version 3.11):

   ```bash
   py -3.11 -m jupyter lab

   ```
____________________________________________________________________









