## Requirements

1. [Install Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/index.html)
2. Download the `dmt-2025-2nd-assignment` directory that contains the datasets, and place at the root of this repository. 

## Installation

1. **Create the conda environment**

   Run the following command in your terminal to create a conda environment based on the `environment.yaml` file:

   ```bash
   conda env create -f environment.yaml
   ```

2. **Activate the environment**
    
    Once created, activate the environment:

    ```bash
    conda activate recommender-expedia
    ```

3. **Add the environment as a Jupyter kernel**

    To be able to select this environment in Jupyter notebooks, run:

    ```bash
    python -m ipykernel install --user --name=recommender-expedia --display-name "Python (recommender-expedia)"
    ```

4. **Launch Jupyter**

    Launch JupyterLab from the activated environment:

    ```bash
    jupyter lab
    ```

5. **Select the kernel in JupyterLab**

    In JupyterLab, when creating a new notebook or opening an existing one, click on the kernel name (top right).

    Select **Python (recommender-expedia)** from the kernel list.