# Lotto 6 aus 49 Number Predictions with statistics and Machine Learning

### Skills in this Notebook shown:
- Data Preprocessing
- Statistical Analysis
- Recurrent Neuronal Networks (LSTM Model)
- Machine Learning Models
- Use Pickle Files to store Predictions or results
- Monte Carlo Simulation and Validation

After storing all Lotto Numbers with their Date of drawing in a CSV (Notebook 1), we make 6 Lotto Number Predictions with 6 different Methods you found in each Notebook. 

If you are only interested in one specific Method then just run Notebook 1-Data_Generation.ipynb and skip to the Notebook for your desire.

Otherwise if you run each Notebook from begin to the end, i have Bonus Notebook Number 8 for you, where you can Simulate your chances of winning with this Predictions. 
However...


### DISCLAIMER:
- This is a Fun Project to Showcase some IT Skills
- Lottery is a total statistically Random Game
- Do not use or let you inspire by this Prediction!
- Gambling can make you addicted! Only Play with Caution!
- I claim no rights, that my outputs would even be near the drawn Numbers

### About the Predictions:
- Please gather some Knowledge about how Lotto 6 aus 49 work to understand the Notebooks
- The Superzahl only appears once per Lottery Ticket - we will Take 7, 5 and 4 randomly for each Ticket
- I will play 6 Fields á 6 Numbers every Saturday and try my luck

### Remember: Lotto is a Random Game, using this Predictions may not increase your chances of winning!!! I just made this as a fun Project for myself


# Set up your Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the Pipeline notebooks.

*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file. 

### **`macOS`** type the following commands : 


- Install the virtual environment and the required packages by following commands:

    ```BASH
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/bin/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```
### **`WindowsOS`** type the following commands :

- Install the virtual environment and the required packages by following commands.

   For `PowerShell` CLI :

    ```PowerShell
    pyenv local 3.11.3
    python -m venv .venv
    .venv\Scripts\Activate.ps1
    pip install --upgrade pip
    pip install -r requirements.txt
    ```

    For `Git-Bash` CLI :
    ```
    pyenv local 3.11.3
    python -m venv .venv
    source .venv/Scripts/activate
    pip install --upgrade pip
    pip install -r requirements.txt
    ```