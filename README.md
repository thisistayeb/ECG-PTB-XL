# Multi-label ECG Classification on PTB-XL Dataset


[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thisistayeb/ECG-PTB-XL/blob/main/PTBXL_CNN.ipynb)

Evaluating a Deep Learning Model for ECG Classification Across Demographics on PTB-XL


This repository contains a Jupyter Notebook for multi-label classification of ECG signals from the PTB-XL dataset using a Convolutional Neural Network (CNN).

## Features

* Performs multi-label classification on the PTB-XL ECG dataset.
* Uses a CNN model.
* Automatically downloads the PTB-XL dataset.
* Can download pre-trained model weights.
* Includes `environment.yml` for easy Conda setup.
* Ready to run in Google Colab (via the badge above).

## Getting Started (Local Setup)

### Prerequisites

* [Conda](https://docs.conda.io/en/latest/miniconda.html) installed.

### Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/thisistayeb/ECG-PTB-XL.git
    cd ECG-PTB-XL
    ```
   
2.  **Create Conda environment:**
    ```bash
    conda env create -f environment.yml
    ```

3.  **Activate environment:**
    ```bash
    conda activate ptbxl
    ```

## Usage

1.  Ensure the `ptbxl` Conda environment is activated.
2.  Start Jupyter Notebook or JupyterLab:
    ```bash
    jupyter notebook
    # or
    # jupyter lab
    ```
3. Open the main notebook file (`PTBXL_CNN.ipynb`).
4. Check `Config` cell
5. Run the cells sequentially. Dataset and weights download are handled within the notebook.

## Google Colab

Click the "Open In Colab" badge at the top to run directly in Google Colab. Installation steps might differ slightly within the notebook for Colab.