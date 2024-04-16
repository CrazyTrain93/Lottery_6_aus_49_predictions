# Pipeline and Pickle File Knowledge provement Project

### Skills in this Notebook shown:
- Data Preprocessing
- Put all Data Processing Steps into a ColumnTransformer
- Build Pipelines around different Column Transformers for Sequencing Operations
- Embedd different Models into my ColumnTransformer Pipeline
- Use Pickle Files to store Predictions or results


I use the famous "Palmer Penguins" Dataset to show my skills in Modelling with Pipelines 
Make sure to get your copy of the Dataset using "pip install palmerpenguins" and import them into your Library before starting

### See Descriptions in the Notebook and Code commentary for all Info you need about how i gathered Pipeline and Transforming Skills

- IN the pure_pipeline_code.py file you will find the whole Process in one Python file Code Block
- IN this Notebook you will find a commented and more detailed Version of the builded Pipelines


## Set up your Environment

Please make sure you have forked the repo and set up a new virtual environment. For this purpose you can use the following commands:

The added [requirements file](requirements.txt) contains all libraries and dependencies we need to execute the Pipeline notebooks.

*Note: If there are errors during environment setup, try removing the versions from the failing packages in the requirements file. M1 shizzle.*

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