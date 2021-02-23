<h1 align="center">Shiny RStudio Overview</h1>
<h4 align="center">Visualization assignments using <a href="https://shiny.rstudio.com/">Shiny</a> at the course of Big Data on the EIT Digital data science master at <a href="https://www.upm.es/">UPM</a> </h4>

<p align="center">
  <img alt="UPM" src="https://img.shields.io/badge/EIT%20Digital-UPM-blue?style=flat-square">
  <img alt="License" src="https://img.shields.io/github/license/angeligareta/shiny-rstudio-overview?style=flat-square" />
  <img alt="GitHub contributors" src="https://img.shields.io/github/contributors/angeligareta/shiny-rstudio-overview?style=flat-square">
</p>

## About

The objective of this project is to practise the usage of [Shiny](https://shiny.rstudio.com/) as a visualization tool. In the first part we followed a tutorial whose purpose was to get in touch with the tool, and in the second part we developed a project of data visualization of the [Madrid Airbnb dataset](https://www.kaggle.com/rusiano/madrid-airbnb-data).

## Madrid Airbnb interactive data analysis tool

### Problem statement

The rise of vacation renting and platforms like Airbnb has created a lot of issues in big
cities, like Madrid. We have decided to analyze a public dataset which offers information
about Airbnb renting, dates and zones. The dataset is public in Kaggle: [Madrid Airbnb dataset](https://www.kaggle.com/rusiano/madrid-airbnb-data).

This dataset is well structured, giving the opportunity of extracting a lot of insight from it,
also it has a considerable volume of data. We chose it because of its great potential and the
various visualizations that could be extracted from it.

### Research questions

The objective of this work is to answer several questions according to the presented
problem domain using a visualization tool. The questions we are trying to answer are:

- How does the renting price change depending on what neighbourhood of
  Madrid the place is? Does it vary too depending on the date?
- What are the neighbourhoods with the best ratings? (taking into account all
  the categories of the scores)
- What are the neighbourhoods with the most number of Airbnb flats? Has this
  changed over time?
- What insights can we gather from the review comments? What do clients
  value more from the Airbnb?

### Implementation

The project was developed using R programming language, [Shiny](https://shiny.rstudio.com/) framework and the library shinymaterial to improve the visual appareance of the input design.

### Discussion

The full report can be found at [project/report.pdf] and it contains the visual approach taken to tackle the research questions, along with a guided use of the application. The interface is publicly available on the website [https://angeligareta.shinyapps.io/shinyairbnb/](https://angeligareta.shinyapps.io/shinyairbnb/) (it can take a moment to load as it is hosted in shinyapps).

## Authors

- **Cristian Abrante** - [CristianAbrante](https://github.com/CristianAbrante)
- **Guillermo Antoñanzas** - [Buhorl](https://github.com/Buhorl)
- **Angel Igareta** - [angel@igareta.com](mailto:angel@igareta.com)
