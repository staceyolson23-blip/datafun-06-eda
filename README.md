# datafun-06-eda

## Overview
This project focuses on **Exploratory Data Analysis (EDA)** using Python. It follows a **repeatable professional workflow** with GitHub for version control, a local **virtual environment** for dependencies, and clear documentation for reproducibility.

---

## Project Initialization

### Repository Setup
1. Created a new public GitHub repository named `datafun-06-eda` with a default `README.md`.  
2. Cloned the repository locally:
   ```bash
   cd ~/Repos
   git clone https://github.com/staceyolson23-blip/datafun-06-eda.git
   cd datafun-06-eda

### Added Common Project Files
Created `.gitignore` and `requirements.txt` files.

# Ignore virtual environment
.venv/

# Ignore Python cache
__pycache__/

# Ignore macOS files
.DS_Store

#### `requirements.txt`
jupyterlab
numpy
pandas
pyarrow
matplotlib
seaborn

---

## Dataset Description

### Dataset Chosen
**Seaborn Penguins Dataset**

### Description
The penguins dataset contains size measurements for three penguin species observed on three islands in the Palmer Archipelago, Antarctica.  
It includes variables such as:
- **species** (Adelie, Chinstrap, Gentoo)  
- **island** (Biscoe, Dream, Torgersen)  
- **bill_length_mm**, **bill_depth_mm**, **flipper_length_mm**, **body_mass_g**  
- **sex**

This dataset is clean and ready for exploration, making it ideal for practicing exploratory data analysis and visualization.

### Source
[Seaborn Built-In Datasets](https://seaborn.pydata.org/generated/seaborn.load_dataset.html)

### Why This Dataset
- Clean and well-structured  
- Includes both categorical and numerical features  
- Suitable for descriptive statistics, visualizations, and exploring relationships  
- Widely used for EDA practice and beginner-friendly
