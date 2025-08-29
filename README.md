# Information Visualisation Individual Project

[![Python](https://img.shields.io/badge/python-3.10-blue.svg)](#)

> This was my final individual project for my Information Visualization course, analyzing the World Recipes dataset through interactive visualizations.
> 
> **Data Analysis**, **Information Visualization**, **Vega-Lite**, **Vega-Altair**, **Word Cloud**

---

## Project Object

The objective of this project is to design and implement a novel information visualization tool that transforms a real-world dataset into interactive visual insights. The project follows a specific framework (e.g., *Why–What–How*) of visualization design to:
- Identify a dataset with multiple quantitative and categorical attributes that supports meaningful analysis.
- Transform and preprocess the data to enable effective encoding and exploration.
- Develop interactive visualizations with expressive encodings and user-driven interactions that facilitate deeper understanding of the dataset.
- Evaluate the visualization by discussing alternative design choices, trade-offs, and the insights obtained from the final implementation.

## Quick Start

### Project Directory Structure

The complete directory structure is as follows:

```bash
infovis_indivproj/
        ├─ InfoVis_project_work.ipynb      # Project source file (Jupyter notebook format)
        └─ README.md
```

### Create Running Environment

I recommend using Conda/Anaconda together with Visual Studio Code as the IDE for running or debugging the Jupyter Notebook code. I have not tested other environments, but if you are familiar with them, you may also set up and run the notebooks by following the instructions. Below, I demonstrate how to configure the environment using my recommended setup:

To reproduce the project results, you first need to have a Conda environment installed (if not, see the [Conda official documentation](https://docs.conda.io/projects/conda/en/stable/) for installation instructions). Then, run the following shell commands to create an environment suitable for executing the Jupyter Notebook code:

```bash
(base) user@device infovis_indivproj % conda create -n infovis-lab-env python=3.10 -y
(base) user@device infovis_indivproj % conda activate infovis-lab-env
(infovis-lab-env) user@device infovis_indivproj % pip install pandas altair matplotlib vega_datasets wordcloud
```

After creating the environment, simply open the Jupyter Notebook in Visual Studio Code and select the Python environment `infovis-lab-env` that you just created as the interpreter. You can then run the notebook code cell by cell.
