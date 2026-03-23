# MedModr
# An Open-Source Mediation & Moderation Software

A statistical application written in R using the Shiny framework for Structural Equation Modeling (SEM) analysis. This tool provides an intuitive interface for conducting mediation and moderation analyses, visualizing path diagrams, and generating professional reports.

## Features

- **Data Import**: Support for multiple file formats (CSV, Excel, SPSS, Stata, RData)
- **Advanced Modeling Capabilities**:
  - **Simple Mediation**: Test indirect effects with single mediator models
  - **Serial Mediation**: Analyze multiple mediators in sequential pathways
  - **Moderation**: Examine conditional effects and interaction terms
  - **Moderated Mediation**: Test conditional indirect effects (moderated mediation models)
- **Interactive Visualization**: Path diagrams with customizable colors and layouts
- **Results Export**: Generate professional Word reports with tables and diagrams

## Prerequisites

### Software Requirements
- **R version 4.5** or higher
- **RStudio** (recommended for local development)

### Required R Packages
The application requires the following packages if it is to be run locally in RStudio. Installation instruction is provided below:


# Local Setup Instruction

# Step 1: Install Required Packages

Launch RStudio on your desktop computer.


# Step 2: Install Required Packages
Run this code in your R console (RStudio) to install required packages:

```r
# Install all required packages
install.packages(c("shiny", "lavaan", "semPlot", "ggplot2", "readr", "readxl", 
                   "haven", "DT", "colourpicker", "officer", "magick", "flextable", 
                   "shinythemes", "shinyjs", "shinydashboard"))
```


# Step 3: Download the Application from the GitHub/Archive repository

GitHub Link: https://github.com/mudassiribrahim12/MedModr/blob/main/app.R

Archive Link: https://archive.org/download/app_20260323/app.R


# Step 4: Open in app.R file

Navigate to File > Open File and select the downloaded app.R file 


# Step 5: Launch the Application

1. In RStudio, click "Run App" and wait. 
2. The application will open in Rstudio, then click "Open in Browser"
