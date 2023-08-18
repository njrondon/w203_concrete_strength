# Modeling the strength of concrete


Concrete is the second most-used substance in the world, after water1. In the construction industry, concrete is the most used building material, and is found in a wide range of structures, such as buildings, bridges, roads, and dams.
The water/cement ratio (WC ratio) is considered the most important characteristic of concrete. This property controls the strength, workability and durability of the product. There is a large body of research showing the importance of this property for the use of concrete.
The design of concrete mixtures depends on the desired characteristics of the concrete for a given application, site requirements and cost considerations.

This study aimed to understand the relationship between different parameters involved in preparing concrete and determining its compressive strength. This understanding can assist in designing concrete mixtures for the desired application reducing costs. We sourced a database with results from testing concrete samples with a wide range of characteristics. We considered the water to cement ratio and the age of the concrete as the independent variables and the compressive strength of concrete as the dependent variable. We adjusted several models to assess the explanatory power of these variables. The impact of adding other ingredients in the binder to improve the strength of the concrete was introduced in the model as categorical variables. We observed that the compressive strength of the concrete has a strong relationship with the water to cement ratio and age. Our results are consistent with the physics of the concrete curing process and can assist in designing concrete recipes to meet desired requirements.

Team Members:
* Javier Rondon
* Daniele Grandi

Documentation is located in:

* The slides in W203-concrete strenght.pdf
* The document in the reports folder W203_Grandi_Rondon_4_14_2022.pdf

## Project Organization

    ├── LICENSE
    ├── README.md          <- The top-level README describing the project aims
    ├── data
    │   ├── raw            <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   └── processed      <- The final, canonical data sets for modeling.
    ├── notebooks          <- .Rmd notebooks. 
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    └── src                <- Source code for use in this project.
        └── data           <- Scripts to download or generate data


Repository structured based on [cookiecutter data science](https://drivendata.github.io/cookiecutter-data-science).
