# VITA (Vehicle-based Intelligent Technology for Atmosphere research) Project Cookbooks

This EVS-ATMOS Cookbook covers methodology and analysis for LDRD-SEED 2023 proposal investigating vechicle-based LiDAR systems for Atmospheric Research

## Motivation

This project will focus on enhancing the current testbed for Advanced Driver Assistance Systems (ADAS) features by incorporating real-time weather data into the pipeline on Argonne’s On-Road Connected and Automated Vehicle (CAV) Testbed and leverage this data for training on-vehicle AI/ML models for weather prediction. 

## Authors

[Joe O'Brien](@jrobrien91), [Nick Goberville](@nGoberville), [Matt Tuftedal](@mtuftedal)

### Contributors

<a href="https://github.com/EVS-ATMOS/vita/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=EVS-ATMOS/vita" />
</a>

## Structure

### Section 1 (Exploration of Meteorological Instrumentation Workflow)
The foundational content includes analysis of meteorological in-situ observations

### Section 2 (Example Vechicle-Based System Workflow )
Example workflows for exploring vechicle-based system observations

### Section 3 (Analysis)
Combined workflow and analysis

### Running on Your Own Machine
If you are interested in running this material locally on your computer, you will need to follow this workflow: 

1. Clone the `https://github.com/EVS-ATMOS/vita` repository:

   ```bash
    git clone https://github.com/EVS-ATMOS/vita.git
    ```  
2. Move into the `vita` directory
    ```bash
    cd vita
    ```  
3. Create and activate your conda environment from the `environment.yml` file
    ```bash
    conda env create -f environment.yml
    conda activate vita-dev
    ```  
4.  Move into the `notebooks` directory and start up Jupyterlab
    ```bash
    cd notebooks/
    jupyter lab
    ```
