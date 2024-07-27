# Financial Services Use in Tanzania (244)

## Project overview

* Objective: Analyzing FDG survey response data on the different types of financial services used in Tanzania to see what relationships are observed and what their overall use are in varying demographics
* Data file: [FDG survey response data](http://syllabus.africacode.net/projects/data-science-specific/data-visualisation/mobile-money-viz/training.csv)
* Project instructions: [here](http://syllabus.africacode.net/projects/data-science-specific/data-visualisation/mobile-money-viz/)
 

## Prerequisites

- Python 3.x
- Jupyter Notebook

## Installation and Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/Thxbiso-DS/financial-service-use-in-tanzania.git
    ```

2. Navigate to the directory:
    ```bash 
    cd financial-service-use-in-tanzania/
    ```

3. Create a virtual environment with a name of your choice or the given name:
   ```bash
   python -m venv financial-service-env
   ```

4. Activate your environment:
   - On Windows:
    ```powershell 
    .\financial-service-env\Scripts\activate
    ```
   - On macOS/Linux:
    ```bash
    source financial-service-env/bin/activate
    ```
5. Install Jupyter in your virtual environment:
    ```bash
    pip install jupyter notebook
    ```
6. Next is to install the kernel for the notebook to run on:
   ```bash
    ipython kernel install --user --name=financial-service-env
   ```
7. Install dependencies:
    ```bash 
    pip install -r requirements.txt
    ``````
    
8. Start jupyter notebook:
    ```bash
    jupyter notebook
    ```

9.  Navigate to http://localhost:8888 in your web browser.

## Use

1. Open the Jupyter Notebook file (`financial_services.ipynb`).
   
2. Under kernels select `financial-service-env`

3. Under run choose choose the option to run all cell.
4. Once you are done, you can close the the browser and enter `deactivate` on your command line 

## Author 
Thabiso Mokgete  
* thabiso.mokgete@umuzi.org

## License 
Copyright © 2023 [Thabiso Mokgete](https://github.com/Thxbiso-DS).<br />
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)