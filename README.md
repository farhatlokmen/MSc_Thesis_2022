# MSc_Thesis_2022
Title: Monitoring of Coastal Water Turbidity in the Presence of Cloud Cover Using Sentinel 2 Imagery with a Machine Learning Approach

This project is an attempt to develop algorithms for filling gaps associated with cloud cover in Sentinel 2 imagery and using the latter to predict turbidity in coastal waterbodies.

The developed code has been organised as follows:
1.  Download Data;
2.  Pre-process Data;
3.  Feature Engineering and Machine Learning Model Development
4.  Analysis of results

A more detailed description of these tasks is provided below. All tasks will be implemented in Python Jupyter Notebook platform.
1.	Download Data: 
Mainly, refers to collecting S2 imagery. Turbidity maps were downloaded from the Copernicus website (further info is described in the pdf document)
	
2.	Pre-process Data: Refers to ensuring that all data is organized in a unified format
This step is about making sure that all collected data share the same geographic extent, spatial resolution, and other characteristics. In addition, it includes the gap-filling algotihm (univariate and bi-variate versions).

3.	Feature Engineering and Machine Learning Model Development:
Refers to preparing training (X) and validation (y) datasets for the different selected months, as well as, implementing different ML models to predict turbidity in the study area.

4.	Analysis of results: 
Refers to the results and discussion sections included in the pdf docuument.
