# Project: Data Science Blog Post

Note to reviewer: The main analysis notebook is **notebooks/02_main.ipynb**

## Motivation

The aim of this project is to explore the results of the Stack Overflow Annual Survey of 2025 (https://survey.stackoverflow.co/ ) and answer a main question: 

**What drives job satisfaction among developers?**


The results are published in this blog:

https://dev.to/chepe_kun_75cd5bb6c79ddb3/cracking-the-code-to-developer-satisfaction-1e8m

## Summary of Results
1. Most developers are highly satisfied with their work
2. Compensation and working on relevant topics are the main contributors to job satisfaction
3. Recognition and leadership are the lowest drivers for job satisfaction
4. High salaries correlate with high satisfaction, but for low satisfaction this trend is less clear
5. Concerns about AI have a clear impact on job satisfaction 


## Files
- data/
    - survey_results_public.zip: A zipped csv file with the survey results
    - survey_results_schema.csv: A table with the schema used to understand the survey categories

- notebooks/
    - 01_data_understanding.ipynb: An initial exploration of the survey, going over multiple questions and creating visualizations.
    - **02_main.ipynb**: **The main analysis notebook**, containing the 4 business questions required to answer the job satisfaction topic.

- images/
    - img_01.png - img04.png: an export of the plots generated in the main analysis
    - blog_image.png: an image generated using Copilot for the blog title

- blog_post/
    - cracking_the_code_to_developer_satisfaction.md: the text of the blog post

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

## Acknowledgements
- Data source: Stack Overflow Survey 2025
- Title image generated with Microsfot Copilot