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

- [data](https://github.com/a1an-na/QTM350_Final_Project/tree/main/data): A cleaned dataset used for the analysis.
- [docs](https://github.com/a1an-na/QTM350_Final_Project/tree/main/docs): The output directory for our website and report.
- [documentation](https://github.com/a1an-na/QTM350_Final_Project/tree/main/documentation): Supporting documentation including codebooks and an entity-relationship diagram.
- [figures](https://github.com/a1an-na/QTM350_Final_Project/tree/main/figures): Contains a compiled notebook of all of our visualization scripts, including PNG files for the figures.
- [final-project-report](https://github.com/a1an-na/QTM350_Final_Project/tree/main/final-project-report) - The Quarto files used to build the final report.
- [final-project-website](https://github.com/a1an-na/QTM350_Final_Project/tree/main/final-project-website) - The Quarto files used to build the final website.
- [README.md](https://github.com/a1an-na/QTM350_Final_Project/blob/main/README.md) – Overview of the project and structure.
- [scripts](https://github.com/a1an-na/QTM350_Final_Project/tree/main/scripts) – Python scripts for data cleaning, visualizations, and the codebook creation.
- Any remaining files are hidden files.

## Website and Report
For this project, we created a Quarto report (output pdf and html) and a Quarto website.

* The website is available through GitHub Pages [HERE](https://a1an-na.github.io/QTM350_Final_Project/).
* For the report, rendered [PDF](https://github.com/a1an-na/QTM350_Final_Project/blob/main/final-project-report/final-project-report.pdf) and [HTML](https://github.com/a1an-na/QTM350_Final_Project/blob/jennifer/final-project-report/final-project-report.html) versions have been added to the `final-project-report` folder for easy access.

Note that the website and report contain the same content, though the website has an animation feature that can't be viewed in the PDF report.

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
5. To render and preview the final website, set the directory to `final-project-website` and run the following from your terminal:
    ```bash
    quarto render
    quarto preview
    ```
   This website report will be generated in GitHub Pages. Navigate to GitHub pages in your browser to view the report. Make sure to select the main branch and the `/docs` folder as the GitHub pages source.
6. To render the final report, set the directory to `final-project-report` and run the following from your terminal:
    ```bash
    quarto render final-project-report.qmd --to pdf
    ```
    This will generate two reports (PDF and HTML) the `/docs/final-project-report` folder. However, they've also been copied beforehand to the `final-project-report` folder for easier access.