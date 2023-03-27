# Data and Analyses for the Paper:
## I SEE NO FUN IN ENTERPRISE SYSTEMS: AN EXPLORATORY STUDY ON THE FIRST IMPRESSION USABILITY AND USER EXPERIENCE
### Published at the ECIS 2023 conference

Authors: Anika Nissen, Mareen Wienand, Reinhard Schütte

<br>
This project includes the raw data for the prior named paper as .CSV table:  ``Raw Data.csv``
* the data includes N = 109 complete datasets in which students evaluated the financial overview pages of SAP S/4HANA with FIORI, Salesforce, Microsoft Dynamics, and Oracle
* the first impressions of these systems were evaluated along the standardized scales of the <a href="https://www.usability.gov/how-to-and-tools/methods/system-usability-scale.html">System Usability Scale (SUS)</a>, and the short version of the <a href="https://www.ueq-online.org">User Experience Questionnaire (UEQ)</a>
* both questionnaires were presented with 7-point Likert scale
<br>
<br>
Further, in the *R* folder, you will find the following files:
* ``ECIS23-CondaEnvironment.yml`` -> this provides the Python and R environment in which the jupyter notebook can be run
* ``DataimportinR.RData`` -> this provides the slightly preprocessed data to be imported by the jupyter notebook or in RStudio
* ``ECIS23_Data_Analyses.ipynb`` -> this is the jupyter notebook which includes all of the demographic analyses and ANOVAs run for the paper

<br>
In the *UEQ Benchmarks* folder, you will find the ``.XLSX`` files for each of the included vendors and their ratings, as well as the comparison of our data to the UEQ benchmark.
