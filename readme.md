## Goldman-Hodgkin-Katz-Equation

This shiny-app is an interactive version of the Goldman-Hodkin-Katz equation used to calcualte the resting potential across a cell membrane in dependence on the relative permeabilities as well as the inner and outer concentrations of different ion species (potassium, sodium, and chloride).

The equation looks as follows:


![Equation](/www/Equation.jpg)

### Interactive user interface
Within the App, you can choose different values for the relative permeabilities as well as the inner and outer concentrations of potassium, sodium, and chloride to explore how changing these variables influences the membrane potential.


![Sliders](/www/Slider.jpg)

Please note that the permeability of potassium cannot be changed, as the permeabilities for sodium and chloride ions are specified relative to that for potassium (P(K) = 1).

### Output
The output panel of the App provides both, graphical output in form of an oscillogram, showing the current membrane potential in mV, and text output of the calculated membrane potential as well as the Nernst potentials for each ion species at the chosen concentrations.

![Output](/www/Output.jpg)

Finally, the App allows you to choose between the following presets:

Resting membrane potential of a cephalopod neuron\
Peak membrane potential of a cephalopod neuron during spiking\
Resting membrane potential of a mammalian neuron\
Peak membrane potential of a mammalian neuron during spiking

 
## Local installation

Make sure that you have R and the following R packages installed on your machine and loaded in your R session:

**shiny**, **shinyWidgets**, **shinyjs**, **ggplot2**, **jpeg**

    # Install packages from the R console via:
    install.packages("shiny")
    install.packages("shinyWidgets")
    install.packages("shinyjs")
    install.packages("ggplot2")
    install.packages("jpeg")
    
    # Load packages from the R console via:
    library(shiny)
    library(shinyWidgets)
    library(shinyjs)
    library(ggplot2)
    library(jpeg)
    
## Using the App locally

Once you have installed and loaded all the packages, you can start the App from the R console using:

    runGitHub( "Goldman-Hodgkin-Katz-Equation", "DaSchmidtke")
    
## Using the App online

An online version of the App can be found here:

German version:
https://daschmidtke.shinyapps.io/Goldman-Hodgkin-Katz-Gleichung/

English version:
https://daschmidtke.shinyapps.io/Goldman-Hodgkin-Katz-Equation/

Access to the shiny server, however, is limited to 25 hours per month, so these links are for testing purposes only. If you want to use the App for longer durations, please use a local installation.

## Author

**Daniel Schmidtke**

