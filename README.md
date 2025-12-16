# Recurrent Kidney Stones Genomics
## Overview
This repository details analyses performed in both UK Biobank (UKB) and All of Us (AoU) examining 'recurrent' kidney stone disease. <br>

## Recurrence Definition
Recurrent kidney stone disease is a complex phenotype as a variety of definitions exist: <br>
<br>
  **Radiological recurrence** = new stone on CT (most accurate measure of 'recurrence') <br>
  **Symptomatic recurrence** = renal colic / intervention (this is the preferred definition from patients, although confounded by asymptomatic stones/post-treatment residual fragments) <br>
<br>
Unfortunately, CT images are not available in either UKB or AoU and therefore this study is limited to symptomatic recurrence only. The same definition was used in both biobanks (colic/intervention) as ascertained by OPCS/ICD/Read codes. We assumed that a **'stone event'** (defined as colic/intervention i.e. symptomatic occurrence) would be complete within 6 months, allowing time for either spontaneous passage or definitive intervention to be completed. <br>
<br>
Each script is a mixture of bash, R and Python - each script explains which language / packages were used at each step <br>

## UK Biobank scripts
<br>
These scripts are prefixed with 'UKB' and demonstrate analyses performed in UK Biobank using a mixture of Rstudio, Jupter notebooks, Swiss Army Knife (SAK) and the terminal interface to UKB tools e.g. regenie. <br>
We also examine the EAU risk stratification for recurrence, which then determines follow-up (see Table 3.3: https://uroweb.org/guidelines/urolithiasis/chapter/guidelines) <br>
<br>

## All of Us scripts
<br>
These scripts are prefixed with 'AoU' and demonstrate analyses performed in All of Us using Jupyter notebooks

## Generic scripts

These are not prefixed e.g. Liftover, and are run on a local machine

