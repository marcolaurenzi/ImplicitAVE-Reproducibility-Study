# Reproducibility Study: ImplicitAVE

This repository contains the reproducibility study for the paper [*ImplicitAVE*](https://github.com/HenryPengZou/ImplicitAVE/tree/main). This study aims to evaluate and validate the results presented in the paper.

## Overview

The implementation provided here reproduces the experiments from the ImplicitAVE paper in a Google Colab environment. The steps below will guide you through running the code.

## Prerequisites

- A Google account is needed to access Google Colab.
- Familiarity with uploading files in Google Colab.

## Setup Instructions

1. **Clone this repository**:  
   Clone this repository to your local machine or directly download the necessary files.

2. **Upload to Google Colab**:
   - Open the Colab notebook provided in this repository (`qwen_vl.ipynb`) in Google Colab.
   - Upload the `environment.yml` file to the root directory of the Colab environment (i.e., `/content`). You can do this using the "Upload" option in the Colab file browser.

3. **Run the Notebook**:
   - Once the `environment.yml` file is uploaded, execute all cells in the Colab notebook in sequence.
   - The code will automatically set up the required environment and run the experiments described in the study.

## Notes

- This study strictly adheres to the configurations and dataset versions as defined in the original *ImplicitAVE* repository (commit [24470e1e19f66be4ea61b6b470e43de47d183a56](https://github.com/HenryPengZou/ImplicitAVE/commit/24470e1e19f66be4ea61b6b470e43de47d183a56)).
- Please ensure you have a stable internet connection to allow Colab to download dependencies during setup.

## Results

The results obtained from running the notebook will be saved in the Colab environment. You can download the results for further analysis.

## Citation

If you use this repository for your work, please cite it as follows:
```bibtex
@misc{laurenzi2024implicitave,
  author = {Alessandro Aldo Marina, Marco Laurenzi},
  title = {ImplicitAVE Reproducibility Study},
  year = {2024},
  publisher = {GitHub},
  journal = {GitHub repository},
  howpublished = {\url{https://github.com/marcolaurenzi/ImplicitAVE-Reproducibility-Study}}
}
```
If you use this repository, also cite the original [*ImplicitAVE*](https://github.com/HenryPengZou/ImplicitAVE/tree/main) paper.
