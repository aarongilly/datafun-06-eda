# datafun-06-eda

## Purpose

This repository is being created in service of Northwest Missouri State University 44608 Module 6 - Exploratory Data Analysis. It will accomplish the following objectives from the module:

- Demonstrate skills with Jupyter, pandas, Seaborn and popular tools for data analytics
- tell a data story and visually present findings in a clear and engaging manner

And, in my case, will include one additional objective:

- Utilizing my long-running quantified self project / data journal for an grad school assignment

For more on my Data Journal, read [this page on my personal site](https://aarongilly.com/Pages/Data-Journal).

## Getting Started

This section walks through the process I took to create this repo and how you could play with it as well.

- Clone this repository
- Navigate a terminal to the repository root directory
- Create a virtual environment, activate it, and install dependencies via these commands:

```shell
python3 -m venv .venv  
source .venv/bin/activate
python3 -m pip install --upgrade pip  
python3 -m pip install --upgrade -r requirements.txt
```

## Organization

Directories & key files.

- `source_data/` - holds sanitized versions of my actual data journal dataset(s)
- `gillespie_eda.ipynb` - required Jupyter notebook iteracting with the data