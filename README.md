# Lotto 6 aus 49 Number Predictions with statistics and Machine Learning

Welcome to the Lotto 6 aus 49 Prediction Project! This repository contains predictive models and analyses for Lotto 6 aus 49, a popular lottery game in Germany. Through statistical analysis, machine learning models, and simulations, we aim to provide insights and predictions to help lottery enthusiasts make informed decisions.

### Features:

Statistical Analysis: Explore historical data to identify patterns and trends in lottery numbers.
Hot Numbers: Predictions based on frequently drawn numbers in previous draws.
Cold Numbers: Predictions based on numbers that have been drawn less frequently.
Longest Time not seen: Predictions based on numbers that have been absent for the longest duration.
Monte Carlo Simulation: Simulate lottery draws using random sampling techniques.
LSTM Model: Long Short-Term Memory model for sequence prediction.
Random Forest Model: Ensemble learning model for accurate predictions.

### Usage:

Explore the notebooks and scripts to understand the methodology and implementation of each predictive model.
Use the provided models to generate predictions for future Lotto 6 aus 49 draws.
Contribute to the project by improving existing models or exploring new methodologies.

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
