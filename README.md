# QTM 350 Final Project: Population Dynamics Across Income Levels

## Group Members:
- Alan Na (2588698)
- Jennifer Gu (2606428)


## Project Overview
This project explores global population dynamics by analyzing three key health-related indicators from the World Bank's World Development Indicators (WDI) database across five countries with varying income levels:

- Countries: Afghanistan, Kenya, India, Brazil, United Kingdom  
- Indicators:
  - Life Expectancy at Birth (`SP.DYN.LE00.IN`)
  - Under-5 Mortality Rate (`SH.DYN.MORT`)
  - Adolescent Fertility Rate (`SP.ADO.TFRT`)

We compare these indicators over time (2000–2023) to evaluate how population health outcomes differ across income levels.


Our research question is: **How do population dynamics compare between countries of different income levels?**

## Repository Structure

This repository is organized into the following folders:

- [data](https://github.com/a1an-na/QTM350_Final_Project/tree/main/data) – A cleaned dataset used for the analysis.
- [docs](https://github.com/a1an-na/QTM350_Final_Project/tree/main/docs) - The output directory for our website.
- [documentation](https://github.com/a1an-na/QTM350_Final_Project/tree/main/documentation) – Supporting documentation including codebooks and an entity-relationship diagram.
- [figures] - PNG files of the plots and tables generated from the scripts.
- [final-project-report](https://github.com/a1an-na/QTM350_Final_Project/tree/main/final-project-report) – Quarto files for the final report.
- [README.md](https://github.com/a1an-na/QTM350_Final_Project/blob/main/README.md) – Overview of the project and structure.
- [scripts](https://github.com/a1an-na/QTM350_Final_Project/tree/main/scripts) – Python scripts for data cleaning, visualizations, and the codebook creation.
- The following files are files to build our website, which is hosted on [GitHub Pages](https://a1an-na.github.io/QTM350_Final_Project/).
  - [_quarto.yml](https://github.com/a1an-na/QTM350_Final_Project/blob/main/_quarto.yml) - The project configuration file.
  - [about.qmd](https://github.com/a1an-na/QTM350_Final_Project/blob/main/about.qmd) - The about page.
  - [conclusion_further_reading.qmd](https://github.com/a1an-na/QTM350_Final_Project/blob/main/conclusion_further_reading.qmd) - The conclusion and further reading page.
  - [data_analysis.qmd](https://github.com/a1an-na/QTM350_Final_Project/blob/main/data_analysis.qmd) - The data analysis page.
  - [data_description.qmd](https://github.com/a1an-na/QTM350_Final_Project/blob/main/data_description.qmd) - The data description page.
  - [index.qmd](https://github.com/a1an-na/QTM350_Final_Project/blob/main/index.qmd) - The home page.
  - [results_discussion.qmd](https://github.com/a1an-na/QTM350_Final_Project/blob/main/results_discussion.qmd) - The results and discussion page.
  - [style.css](https://github.com/a1an-na/QTM350_Final_Project/blob/main/styles.css) - The CSS file for styling the website.
- Any remaining files are hidden files.

## Getting Started

These instructions will help you set up the project locally.

1. Navigate to your preferred directory in the terminal.
2. Clone the repository and set the following directory:
    ```bash
    git clone https://github.com/a1an-na/QTM350_Final_Project
    cd QTM350_Final_Project
    ```
3. In the scripts folder, open the `QTM350_Final_Project.ipynb` Jupyter Notebook to run the data cleaning scripts. This will create the dataset used for our analysis.
4. To create other visualizations, open and run the code in the `life_expectancy.ipynb`, `under_5_mortality.ipynb`, and `adolescent_fertility.ipynb` notebooks.
5. To render and preview the final report, run the following from your terminal:
    ```bash
    quarto render
    quarto preview
    ```
6. The final report will be generated in github pages within the `final-project-report` directory. Navigate to GitHub pages in your browser to view the report.