# CWL 

CWL workflows for generating GRAY (2013,2017) and UHNBreast (2017,2019) PharmacoSets(PSets) using the *PharmacoGx* toolset.
<br/>
<br/>
PSet is a R data object that will contain cell line/drug curations, drug sensitivity (AAC,IC50), and molecular profiles (RNA-seq, methylation, RPPA) for a given pharmacogenomic dataset above. Data object can be used to further cancer research.
<br/>
<br/>
To execute a workflow, perform the following command within the workflow directory of a respective dataset (example for GRAY 2017 dataset):
<br/>
<br/>
`cwltool getGRAY2017_Workflow.cwl getGRAY2017_Workflow.yml`


**NOTE**: Methylation data for GRAY 2013 and 2017 are compressed for uploading to GitHub. Therefore, please unzip the raw data file before execution.
<br/>
<br/>
These pipelines and generated PSets can be found on **Code Ocean** and **Harvard Dataverse** at the following links:
<br/>
<br/>

Code Ocean: https://doi.org/10.24433/CO.7378111.v1
<br/>
<br/>
Harvard Dataverse: https://doi.org/10.7910/DVN/BXIY5W
