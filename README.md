<div align="center">

# Data Visualization with Matplotlib

### Practical Python notebooks for building clear, informative visualizations

![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-visualization-11557C?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Notebooks-Jupyter-F37626?logo=jupyter&logoColor=white)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**A hands-on collection of Matplotlib notebooks using sports and statistical datasets.**

</div>

---

## Overview

This repository contains Jupyter notebooks for learning Matplotlib and creating data visualizations in Python. It moves from foundational plotting concepts to more advanced layouts and styling, with examples using cricket/IPL data and the Iris dataset.

The notebooks are intended for practice and exploration. Run the cells, inspect the charts, and adjust the data or styling to see how the visualizations change.

## Repository structure

```text
.
├── 01_matplotlib.ipynb
├── 02_Advance_matplotlib.ipynb
├── datasets-session-23/
│   ├── batter.xls
│   ├── batsman_season_record.xls
│   ├── fours_sixes.xls
│   ├── gayle-175.xls
│   ├── sharma-kohli.xls
│   ├── vk.xls
│   └── big-array.npy
└── datasets-session-24/
    ├── IPL_Ball_by_Ball_2008_2022.xls
    ├── batsman_season_record.xls
    ├── batter.xls
    └── iris.xls
```

## Topics and examples

The notebooks explore Matplotlib's Figure and Axes model, plotting and styling, and arranging charts into multi-panel layouts. Examples described for this repository include:

- Comparing batsmen and visualizing cricket/IPL performance data.
- Exploring scoring and boundary data, including fours, sixes, and high-scoring innings.
- Plotting historical IPL ball-by-ball data.
- Visualizing the Iris dataset with scatter and distribution plots.
- Loading a NumPy `.npy` array for matrix or heatmap-style visualization.

The exact charts and concepts depend on the content of each notebook.

## Requirements

- Python 3
- Jupyter Notebook
- Matplotlib, NumPy, and Pandas
- `xlrd` to read the included legacy `.xls` files through Pandas
- `openpyxl` only if you also read `.xlsx` files

Install the packages with:

```bash
python -m pip install matplotlib numpy pandas xlrd openpyxl notebook
```

On Windows, if `python` is not recognized, use `py`:

```powershell
py -m pip install matplotlib numpy pandas xlrd openpyxl notebook
```

> **Excel engine note:** Pandas uses `xlrd` for `.xls` files. `openpyxl` is for `.xlsx` files; it does not read the `.xls` files listed here.

## Getting started

1. Clone this repository. Replace `OWNER` and `REPOSITORY` with the values from your GitHub URL:

   ```bash
   git clone https://github.com/OWNER/REPOSITORY.git
   cd REPOSITORY
   ```

2. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

3. Open `01_matplotlib.ipynb` for the introductory material or `02_Advance_matplotlib.ipynb` for the advanced notebook.

Keep the dataset folders in their current locations so notebook-relative file paths continue to work.

## Dataset notes

The repository includes `.xls` spreadsheets and a `.npy` array. Check the source and terms of use for each dataset before redistributing it. The MIT license applies to original code and documentation in this repository; third-party datasets may have separate licenses or restrictions.

## License

This project is licensed under the [MIT License](LICENSE). If the repository does not yet contain a `LICENSE` file, add the MIT license before relying on this badge or statement. Third-party datasets remain subject to their respective terms.
