## Setup Instructions
1. [Download](https://git-scm.com/downloads) and Install Git
2. [Download](https://www.anaconda.com/download/success) and Install Anaconda (or Miniconda if you do not have enough memory).
3. Clone the [repo](https://github.com/ed-donner/llm_engineering) and run the below command to install the dependencies.
	```powershell
	conda env create -f environment.yml
	```
4. After installing the dependencies run the below command to activate the environment.
	```powershell
	conda activate llms
	```
	Note: The prompt in PowerShell window should change from (base) to (llms) as mentioned in the environment.yml file. 
5. Run `jupyter lab` in PowerShell to open the jupyter lab window.

For detailed setup instructions, visit [here](https://github.com/ed-donner/llm_engineering/blob/main/SETUP-PC.md)

Note: If you do not want to run anaconda in your machine. Take a look at [04 - Setup Virtualenv](04%20-%20Setup%20Virtualenv.md) for the alternative setup.

