# MSc_Thesis_2022
## Title
Monitoring of Coastal Water Turbidity in the Presence of Cloud Cover Using Sentinel 2 Imagery with a Machine Learning Approach

## Set-Up
This project is an attempt to develop algorithms for filling gaps associated with cloud cover in Sentinel 2 imagery and using the latter to predict turbidity in coastal waterbodies.
The code was developed using Python Jupyter Notebook platform. A description of the implemented tasks is provided below:
1.	Download Data: Refers to collecting S2 imagery. The acquisition of other data (e.g. turbidity maps) was done manually and is described with more detail in the pdf document.
	
2.	Pre-process Data: Refers to ensuring that all data is organized in a unified format. This step is about making sure that all collected data share the same geographic extent, spatial resolution, and other characteristics. In addition, it includes the gap-filling algotihm (univariate and bi-variate versions).

3.	Feature Engineering and Machine Learning Model Development: Refers to preparing training (X) and validation (y) datasets for the different selected months, as well as, implementing different ML models to predict turbidity in the study area.

4.	Analysis of results: Refers to the results and discussion sections included in the pdf docuument.
