# 👩‍🔬 Logistic Regression Analysis: Determinants of Women as Primary Source of Revenue
![banner](banner.jpg)



## Table of Contents

-   [Technologies Used](#technologies-used)
-   [Description](#description)
-   [Objectives](#objectives)
-   [Dataset](#dataset)
-   [Analysis Results](#analysis-results)
-   [Installation](#installation)
-   [Usage](#usage)
-   [Project Structure](#project-structure)
-   [Contact me](#contact)
-   [Conllaborators](#collaborators)
-   [License](#license)

---

## Technologies Used

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)  ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)  ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![Statsmodels](https://img.shields.io/badge/statsmodels-4051b5?style=for-the-badge&logo=statista) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white) ![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)



---
## Description
This project aims to analyze the determinants for a woman being the primary source of revenue in a household using data from the "Conditions de Travail 2013" survey. The analysis will be focused on individuals living in couples in the same household.

### Objectives
The objective of the project is to analyze, based on the 2013 Working Conditions survey, the determinants for a woman being the primary source of revenue in the household.
1. Data Exploration & Management: Explore the dataset and the available data and handle missing data.
2. Feature Selection: The dataset presents 541 Columns/Features. A selection needs to be made to be able to conduct further analysis.
3. Build and evaluate a logistic regression model to identify significant predictors of a women being the primary source of revenue in the household.

### Dataset

- **Source**: Conditions de Travail 2013 (Volet "Actif")
- **Initial Dataset Size**: 33,673 individuals
- **Filtered Dataset**: Individuals living in couples at the same household

---
## Analysis Results

#### The results are in a presentation in the following link: [Presentation Link](https://www.canva.com/design/DAGM-nDYEGo/JS0MPodVK23CHKAz3wkHsw/view?utm_content=DAGM-nDYEGo&utm_campaign=designshare&utm_medium=link&utm_source=editor)
The presentation is also available as the pdf: 
```
Results_Analysis.pdf
```
---
## Installation

> [!IMPORTANT]
> The project was done on Python 3.11.6

To run this project locally, follow these steps:

1. Clone the repository:
```sh
# Clone the repository
git clone https://github.com/Medkallel/Logistic-Regression-Analysis
# Navigate into the directory
cd Logistic-Regression-Analysis
```
2. Install the required dependencies:
```sh
# Install the requirements
pip install -r requirements.txt
```

---
## Usage 
```
The analysis data is already available in the notebook but you can run it all
```
> [!TIP] 
> The notebook could take up to 15 minutes to run. Be patient :) 

---
## Project Structure
```
Here's a visual representation of the structure:
📦Project
 ┣ 📁Data/
   ┗ 🗃️individus_ct2013.sas7bdat
 ┣ 📁Doc/
 ┃ ┗ 📄Dictionnary_of_Variables.pdf
 ┣ 🐍Data_Analysis_Notebook.ipynb
 ┣ 📄requirements.txt
 ┣ 📄Results_Analysis.pdf
 ┗ 📄README.md
```
---
## 📫 Contact me
<p>
<a href="https://www.linkedin.com/in/mohamed-kallel/">
<img alt="LinkedIn" src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a> 
<br>
</p>

---
## Collaborators

This project is the result of the collaborative efforts of a diverse and talented team. Each member has contributed significantly to different aspects of the project, from initial research and data collection to final analysis and presentation.
- **Jean Christophe Rigoni**
- **Simon Pierre Rodner**
---
## License
This project is under the **CC BY-NC 4.0 License**. Check the licence file for more info. <br/>
[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

