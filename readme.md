## Goldman-Hodgkin-Katz-Equation

This shiny-app is an interactive version of the Goldman-Hodkin-Katz equation used to calcualte the resting potential across a cell membrane in dependency of the relative permeabilities as well as the inner and outer concentrations of different ion species.

## Installation

Make sure that you have the following R libraries installed on your machine and loaded in your R session:

    install.packages("shiny")
    install.packages("shinyWidgets")
    install.packages("shinyjs")
    install.packages("ggplot2")
    install.packages("jpeg")
    
    library(shiny)
    library(shinyWidgets)
    library(shinyjs)
    library(ggplot2)
    library(jpeg)test

## Start the App

Once you have installed and loaded all the libraries, you can start the App from the command line using:

    runGitHub( "Goldman-Hodgkin-Katz", "DaSchmidtke")
