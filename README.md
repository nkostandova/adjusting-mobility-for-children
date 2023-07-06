# adjusting-mobility-for-children
Code and data to accompany manuscript on adjusting mobile phone data to account for children's travel survey

# The following files are included:

 ## 1. set_up_ICs.Rmd
 Run the chunks in this file first. This will read in inputs, set up initial conditions and parameters.
 Note that the raw mobility dataset is NOT available, but we have made available the simulated dataset after fitting the departure-diffusion model.
 The Rmd will NOT knit; please run the chunks.
 
 ## 2. simulations.Rmd
 This is the code that simulates the transfusion models under different scenarios. The code using absolute mobile phone data (absolute CDRs) will NOT run, 
 but the code where mobility matrices are from departure-diffusion model WILL. You can run those chunks.  
 
 ## 3. functions_compartm.R
 This had the functions for simulations and for processing the output of the simulations. Include it as source code when running simulations.Rmd
 
 ## 4. figures_and_tables.Rmd
 This has code for making some of the figures and roads using the output from functions_compartm.R
 
# Inputs
 
 Inputs are stored in the "inputs" folder. Note that the shapefile is not included due to large size; it can be downloaded
 from https://data.humdata.org/dataset/cod-ab-zmb?  
   
If you have any questions, please feel free to reach out to Natalya Kostandova (Github: nkostandova, email: nkostan1@jh.edu).
