# datafun-06-eda

## Purpose

This repository is being created in service of Northwest Missouri State University 44608 Module 6 - Exploratory Data Analysis. It will accomplish the following objectives from the module:

- Demonstrate skills with Jupyter, pandas, Seaborn and popular tools for data analytics
- tell a data story and visually present findings in a clear and engaging manner

And, in my case, will include one additional objective:

- Utilizing my long-running quantified self project / data journal for an grad school assignment

For more on my Data Journal, read [this page on my personal site](https://aarongilly.com/Pages/Data-Journal).

## Development Log

This section walks through the process I took to create this repo.

- Created a new repository directly in [GitHub](https://github.com/)
  - Included a `README.md`, a `.gitignore` for Python, and an MIT License
- Opened VS Code and utilized its GUI to clone my newly created repository to my computer
- Navigated a terminal to the repository root directory
- Created a virtual environment, activated it, and installed dependencies via these commands:

```shell
python3 -m venv .venv  
source .venv/bin/activate
python3 -m pip install --upgrade pip  
python3 -m pip install --upgrade -r requirements.txt
```

- Added my own `requirements.txt` including:

```plaintext
jupyterlab
pandas
pyarrow
matplotlib
seaborn
```

- Created a Jupyter notebook `gillespie_eda.ipynb` and added its first cell, a Markdown cell explaining what all this is.
- Created a directory for holding my source data, aptly titled `source_data`
- Next up: Open my personal Data Journal and ask myself a bunch of existential questions about personal transparency and what I did or did not want to share. I mung my quantified self data and create several sanitized derivative datasets, to add to `source_data` directory.

## Organization

Directories & key files.

- `source_data/` - holds sanitized versions of my actual data journal dataset(s)
- `gillespie_eda.ipynb` - required Jupyter notebook iteracting with the data