
Note: This is an alternative setup to [03 - Setup Anaconda](03%20-%20Setup%20Anaconda.md). If you already have anaconda setup done, you will not need this.

## Setup Instructions
1. [Download](https://www.python.org/downloads) and Install Python. (Compatible version with all dependencies as of 24-09-2025 is Python 3.11).
2. [Download](https://visualstudio.microsoft.com/visual-cpp-build-tools/) and install Microsoft C++ Build Tools.
3. Clone the [repo](https://github.com/ed-donner/llm_engineering) and run the below command at the root of the directory to install the dependencies.
	```powershell
	python -m venv llms
	```
4. Activate the virtual environment by running the below command.
	```powershell
	llms\Scripts\activate
	```
5. Run the commands below to install the dependencies.
	```powershell
	python -m pip install --upgrade pip
	pip install -r requirements.txt
	```
6. Run `jupyter lab` in PowerShell to open the jupyter lab window.