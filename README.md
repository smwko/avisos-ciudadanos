# Citizen Notices

Would you prefer to read this documentation in Spanish or in English?

- [Haz clic aquí para ver la versión en español](README-es.md)
- [Click here to view the English version](README.md)

### Index
- [👋 Introduction](#introduction)
- [📑 Description](#description)
- [🌟 Features](#features)
- [ℹ️ About the Database](#%E2%84%B9about-the-database)
- [⚙️ Project Setup](#%EF%B8%8Fproject-setup)
- [⚖️ License](#%EF%B8%8Flicense)
- [📫 Contact](#contact)

## 👋Introduction
Welcome to the repository of our Citizen Notices project! This project was carried out by [@flotrigo](https://github.com/flotrigo) and me as part of our Applied Mathematical Engineering program in Data Analysis (Data Science) at Universidad Europea de Madrid during the 2nd year of our degree, from September 2022 to December 2022.

## 📑Description
The purpose of this project is to search for an open database and subject it to a series of processes, including data cleaning, comprehensive analysis, and extraction of meaningful conclusions.

In this project, we will focus on obtaining a relevant and reliable database. We will then apply data cleaning techniques to ensure that the data is consistent and free of errors. Once the cleaning stage is completed, we will carry out a thorough study of the data, applying appropriate analysis techniques and methods to extract valuable information.

Our ultimate goal is to obtain meaningful conclusions from this database. By systematically and deeply analyzing the data, we will be able to discover patterns, trends, and relationships that allow us to gain insights and make informed decisions.

## 🌟Features
- Utilization of the **pandas** and **numpy** libraries for data preparation.
- Performing an **exploratory analysis** of the variables and visualization of graphs (such as scatter plots, bar charts, and box plots) using the **matplotlib** and **plotly** libraries.
- **Comparison of results** in the years 2020, 2021, and 2022. *Note: The data for 2022 from the attached CSV file is only available until September*.
- Performing simple **web scraping** on Wikipedia to obtain the list of districts in the Community of Madrid, along with their respective population data.
- Creating **interactive maps** of the Community of Madrid and **heat maps** using the **folium** library, where the represented points vary in size according to the number of cases.
- Additionally, a dataset of the districts of the Community of Madrid is manually created since it doesn't exist: [Madrid Districts - Latitude and Longitude](https://www.kaggle.com/datasets/jjnscjj/distritos-de-madrid-latitud-y-longitud)
- Detailed information about **security and privacy** in the project.

## ℹAbout the Database
The selected database has been collected from the following page of the Madrid City Council: [Citizen Notices](https://datos.madrid.es/portal/site/egob/menuitem.c05c1f754a33a9fbe4b2e4b284f1a5a0/?vgnextoid=fd6112695c6bb410VgnVCM1000000b205a0aRCRD&vgnextchannel=374512b9ace9f310VgnVCM100000171f5a0aRCRD&vgnextfmt=default). This database focuses on the reports of incidents reported by citizens of the Community of Madrid and on those incidents resolved by the City Council. They are two datasets related to reports of incidents in public areas, covering areas such as cleaning, parking meters, lighting, waste collection, sidewalks and roads, green areas, and others. These reports have been transmitted to the City Council through various channels, such as the telephone number 010-Madrid Line, the mobile application 'Avisos Madrid,' and the website www.madrid.es.

One dataset contains the reports received during a specific period of time, while the other dataset includes the processed reports during that period, regardless of the opening date of the reports.

## ⚙️Project Setup
To install and test the project locally, follow these steps:

1. Clone the repository with the following command: `git clone https://github.com/smwko/avisos-ciudadanos.git`.
2. Install the required libraries using `pip install [library name]` if using the terminal or `!pip install [library name]` if using the Jupyter notebook (.ipynb).
3. Access the notebook named reporte-incidencias.ipynb by opening Jupyter Notebook or searching in the browser: `http://localhost:8888/tree`.

## ⚖️License
This project is licensed under a [Creative Commons Attribution-NonCommercial 4.0 International](https://creativecommons.org/licenses/by-nc/4.0/) license. This means that you can use, modify, and distribute the project as long as it is not for profit or commercial purposes. Additionally, if you use this project, you are required to attribute it to the original authors.

## 📫Contact

If you have any questions, suggestions, or feedback, feel free to get in touch with us!

---

Let's work together to create safer, cleaner, and more vibrant public spaces. Thank you very much for your interest!
