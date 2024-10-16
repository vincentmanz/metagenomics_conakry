# metagenomics_conakry

Course material for the workshop in metagenomics

## Before the course:

1. **Install R and RStudio for your operating system**:
   - [Install R](https://cran.rstudio.com/)
   - [Install RStudio](https://posit.co/download/rstudio-desktop/)

2. **Download the course material**:
   - Download the course material to your `Documents` folder with this [link](https://github.com/vincentmanz/metagenomics_conakry/archive/refs/heads/main.zip), or by running the following command:
   
     ```bash
     git clone https://github.com/vincentmanz/metagenomics_conakry.git
     ```
3. **Open the R project**
     
     Double click on *metagenomics_Conakry.Rproj*, it should open in Rstudio by itself. 

4. **Setup RStudio**:
   - In the R console, install `renv`:
   
     ```r
     install.packages("renv")
     ```

   - Set your working directory to the location of the course material.
   
     - **For Unix/macOS systems**:
       ```r
       setwd("~/Documents/metagenomics_conakry")
       ```

     - **For Windows systems**:
       ```r
       setwd("C:/Users/YourUsername/Documents/metagenomics_conakry")
       ```

     Be sure to replace `YourUsername` with your actual Windows username.

   - Load the environment by running the following command in your console:
   
     ```r
     renv::install(exclude = c("physeq", "microbiome", "mia"))
     ```

