# Roadmap for Rishit Avadhuta's Implementation Project of the Graphlet Screening Method in the GWAS Context
### Rishit Avadhuta, 2024-25

This project aims to utilize `Graphlet Screening` as a method for high-dimensional variable selection as a method of 
constructing linear/multiple regression models using genomic data stored in the `MatrixTable` format from Python 
package `Hail`. 

## Phase 1: Experimentation with the existing Graphlet Screening algorithm to determine linear regression factors

Main objective: Use GS to generate a sample linear regression model and utilize it under a general use case to 
understand its input and output variables

1. Identify the different functions and their purpose in fulfilling the GS method. <br>
Date accomplished: 10/7/24
2. ~~Create a map of the algorithm to understand its functions at a base level.~~ <br>
~~Date accomplished: N/A~~
3. Attempt simulation given pre-existing data set or uses.
   - demolterGS.R
   - DemoGS.R
   - Perhaps using some other public + analyzed data set with some chosen variables? <br>
       Date accomplished: 10/7/24
4. Experiment with changing these values <br>
	Date accomplished: 10/7/24
5. Change the sparsity and the minimum signal strength to display GS effectiveness in comparison to regular multiple linear regression
    <br> Date accomplished: ...

### TIMELINE TARGET
<p class="timelineTarget">
By now, we are in November and have a base-level understanding of the different methods of the system and how to use them.
</p>

## Phase 2: Manual integration with built-in hail tutorials (GWAS tutorial)

Main objective: Use GS with hail GWAS tutorial data as input instead and compare to correlations found through regular hail analysis

1. Proof of concept by swapping between Python (hail) and R (GS) to configure a working linear regression analysis model using the GWAS tutorial. Manually plug values in.
2. Compare results using the GS model to the hail model.

### TIMELINE TARGET
<p class="timelineTarget">
By now, we are in December with a finished grant proposal and base-level data for basic proof of concept.
</p>

## Phase 3: Creation of Python packages with functions to enhance the built-in hail tutorial

Main objective: Convert the GS model into Python so that Hail’s data tables can be directly plugged in.

1. Convert GS to Python
2. Format Hail MatrixTables for GS in Python
3. Attempt the GWAS tutorial again with Python methods automatically generating the result
4. Compile a package with all the created functions
5. Determine the accuracy of the model by comparing the two results and start looking into differentiating criteria

### TIMELINE TARGET
<p class="timelineTarget">
By now, we are in mid to late January with valid results and comparison analysis ready to present.
</p>

## Phase 4: Test for use with All of Us genomic data

Main objective: Use the GS Python package in a realistic environment to prove its worth in genomic analysis

1. Insert the package into the All of Us workbench environment with already researched data.
2. Use the package within the environment to plug into Hail first
3. After plugging into Hail, use the Python package to return a model.
4. Observe results or correlations, if any.
5. Determine objective measurements of effectiveness/improvement made by the model

### TIMELINE TARGET
<p class="timelineTarget">
By now, we are in late February and are ready to present. 
This section is not necessarily required to finish the project.
</p>
