# something-eventually
Will eventually have a greater purpose/problem to solve, but at the moment want to use to familiarize myself with the following tools:
    - circleci
    - docker
    - poetry
    - pytest
    - airflow
    - streamlit

# Create Env
Will eventually use poetry but for now using conda.

To build conda environment:
conda env create -f conda.yml
conda activate something-eventually

To remove and rebuild conda environment:
conda deactivate
conda env remove -n something-eventually
conda env create -f conda.yml
