# SP2024-FP01-Glaciers
## Project Members: 
- Callum (callumh-c)
- Finley (fwolff03)
- Nate (NathanSedmak)
- Wade (wadekah)
## Summary: 
We used ice sheet thickness data collected by plane from the NSIDC to analyze changes in Greenland's glaciers from 1993 - 2019. Based on the available data, we found that there has been a reduction in coastal ice thickness, while interior ice has remained relatively unchanged. Overall, the spatial observation of our data was limited by the changing flight paths and by extension location of the available data. The data also showed a clear maximum relationship between ice thickness and elevation, where ice sheets tended not to exceed a thickness of roughly 3000 meters minus the elevation. Additionally, our data showed no correlation between latitude and ice thickness. This is likely due to the varying topography and coastlines of the survey area, as well as the variance in data lcoation. The limited data location and consitency hinders the potential utilization of this data. Continued collection and improvement of the quality of collected data are key to the continuance of studying Greenland's cryosphere.

## Background Infomation:


## Problem statement, question(s) and/or objective(s):

We are going to model the change in Greenlandian Glaciers over time. To do this, we will use the included libraries to develop an animation of glacier coverage over time.

#### Questions:

- How has the distribution and thickness of glaciers in Greenland changed in the recent past (~30 years)?

- How does a glacier's elevation affect its thickness?

- What additional insights can we gain from past glacier data?

#### Anaylze the specifics of the greenland glacier:

- Loss of mass/year
- Displacement/year

#### Objectives:

- Cleanly organize the different datasets into individual dataframes

- Convert any necessary columns to Numpy np.ndarrays if vector math is needed

- Use Matplotlib to create simple plots of our data

- Use Cartopy to create a scatter plot of the locations of data collected.

- Use Cartopy to create a heatmap of glacier presence in Greenland over time

## Datasets you will use (with links, if available):

We will be using this dataset from the NSIDC. This dataset contains radar measurements of ice thickness across Greenland from 1993 to 2019. These measurements were taken across several plane flights each year. 
[NSIDC Greenland Ice Thickness Dataset](https://nsidc.org/data/nsidc-0625/versions/1)


## Tools/packages you’ll use (with links):
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Cartopy](https://pypi.org/project/Cartopy/)

## Planned methodology/approach:
We will use Matplotlib to create simple plots of our data and then use these plots to help in the creation of a heatmap over time. We will use Folium to display coverage of the Greenland Ice Sheet at each of the times we will analyze. We will animate the coverage of the ice sheet to show change over time. We will also compare these images to quantitatively describe the change in the ice sheet over time. 

## Results:
We found that mass loss occurred on the coast of Greenland between 1993 ad 2019, while inland glaciers appeared to remain mostly unchanged. We found that there is a ratio whereby ice thickness decreases by one meter for every meter increase in bottom elevation. Our investigation found a maximum bottom elevation of 3000 m, though this finding is likely influenced by the chosen survey areas. There appears to be no consistent relationship between latitude and ice thickness. 

## Contribution Statement:
Finn created figures 1 and 2 (locations of data collected and average ice thickness), Nate created figure 3 (ice thickness map), Callum created figure 4 (bottom elevation vs ice thickness), and Wade created figure 5 (latitude vs ice thickness). Callum, Nate, and Finn worked together to create the final version of the README.md file and much of the initial draft of this file. Wade created the initial list of research questions which we submitted for the first project checkpoint. The environment.yml file was created by Finn, the overall structure of the repo as well as the pngs of the figures were created by Nate. Callum, Nate, and Finn worked to find and upload the data for this project. 

## References:


