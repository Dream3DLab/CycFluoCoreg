# CycFluoCoreg

Affine + Bspline based coregistration for 2D cyclic immunofluorescence imaging.

---

## Overview

This repository provides tools to perform affine and B-spline-based coregistration on cyclic immunofluorescence imaging data. The project includes utilities to read `.lif` files, perform image processing, and align images across cycles using advanced registration techniques.

---

## Installation

To use this repository, you'll need to install Miniforge or Miniconda and set up a Python environment.

### Step 1: Install Miniforge or Miniconda

**Option A: Install Miniforge (recommended)**

1. Download the appropriate installer for your operating system from the [Miniforge GitHub releases page](https://github.com/conda-forge/miniforge/releases).
2. Run the downloaded file and follow the installation instructions.

**Option B: Install Miniconda**

1. Download the Miniconda installer for your OS from the [Miniconda downloads page](https://docs.conda.io/en/latest/miniconda.html).
2. Run the installer and follow the instructions.

### Step 2: Create the `coreg` Environment

1. Open a terminal (or Anaconda Prompt if using Windows).
2. Navigate to the directory where you've cloned this repository:

    ```bash
    cd path/to/your/repo
    ```

3. Run the following command to create a new conda environment named `coreg` using the provided YAML file:

    ```bash
    conda env create -f coregenvironment.yml -n coreg
    ```

4. Activate the environment:

    ```bash
    conda activate coreg
    ```

This will install all the required dependencies for CycFluoCoreg into the `coreg` environment.

---

## Usage

After activating the environment, you can open jupyter notebook in your browser by typing the following into the terminal:

```bash
jupyter notebook
