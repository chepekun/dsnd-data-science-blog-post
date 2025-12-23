# Project: Data Science Blog Post

This project contains the notebooks used to explore the data and write the a blog post with an analysis of the Stack Overflow Annual Survey of 2025.

## Getting started

The CRISP-DM process is followed in these steps:
* **01 Data Gathering**: The csv files with the survey results and schema were downloaded from https://survey.stackoverflow.co/ into the /data folder.
* **02 Data Understanding**: The data is loaded and explored in the notebook 01_data_understanding.ipynb in the /notebooks folder.
* **03 Data Preparation + Modelling**: Some results from the data exploration section were selected to write the blog post.
    This is done in the 02_story.ipynb. Within the story the data is cleaned and analyzed.
* **04 Deployment**: An image was generated using Copilot for the blog, stored in the /data folder. 
    The blog post was uploaded to a platform. 
   

## Structure

The project has the following folders:
* **data**: contains the data in csv from the Stack Overflow Annual Survey of 2025 and the generated image for the blog.
* **notebooks**: contains the notebooks for data exploration and writing the blog.
* **src**: contains packages common to all notebooks (Not used in this project!)

## Dependencies

Packages required for the analysis:
```
numpy
pandas
scipy
matplotlib
seaborn
```

Packages required for the IDE
```
ruff
pyright
setuptools
ipykernel
ipython
```

## Installation

There are two ways to install this project:
* Use uv (https://docs.astral.sh/uv/) and sync with pyproject.toml
* Run pip install -r /requirements.txt

## License

[License](LICENSE.txt)