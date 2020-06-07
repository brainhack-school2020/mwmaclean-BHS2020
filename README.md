# mwmaclean-BHS2020
This project is part of the Brainhack School 2020

Team contributors: Michèle MacLean & Brainhack School members

![BrainHack School](images/bhs2020.png)

## Summary 

Hello! I'm currently a PhD student in Cognitive Neuroscience at l'Université de Montréal. My main focus is to study cortical visual impairment using MRI techniques. Damage to the primary visual areas can result in clinical blindness and prompt a cascade of dynamical structural and functional alterations of the neural networks at both the cortical and subcortical level. Following this damage, individuals can sometimes preserve the ability to non consciously process visual information in their blind field, a striking phenomenon know as blindsight. My fascination resides in understanding how the brain can process visual information without conscious awareness.

The overall goal of the current project is to use the tools to organize, analyze and visualize MRI data learned during the BrainHack Summer School.  

![Logo Udem](images/logo_UdeM.png) ![Logo UNF](images/logo_unf.png)

## Project definition 

### Background

This project will explore the steps for analyzing diffusion magnetic resonance imaging data starting from the raw data all the way to data visualization. The long term goal is to investigate the consequences of a primary visual cortex lesion on cerebral reorganization using both diffusion MRI and/or resting state functional connectivity. For this, I will use previously acquired data from l'Unité de Neuroimagerie Fonctionnelle in Montréal. 

The following objectives represent the next planned steps: 
The first steps will be to try to 1) organize the MRI data in a BIDS friendly format and then 2) preprocess the data. Then, I plan to explore 3) analyzing diffusion MRI (i.e. dwi tracking) and 4) perform data visualization.

### Tools 
This project will rely on the following:
* GitHub for creating a repository & assembling all the resources.
* Bash terminal
* Visual studio code
* BIDS as a standard to organize the neuroimaging data
* Python 
* Docker container to run preprocessing pipeline and basic tracking
* DIPY for preprocessing and basic tracking of diffusion weighted images (DWI)
* Jupyter Notebook to document the process and for data visualization
* Data visualization tools (e.g. Nilearn, Plotly, Numpy, Matplotlib, Seaborn).


### Data 
MRI data was acquired with a high resolution 3 Tesla scanner (Siemens Trio system) and consists of a preliminary data set of 5 subjects, including 1 individual with cortical visual impairment with blindsight and 4 neurotypical controls. For each participant, raw structural MRI, resting state functional connectivity, fMRI and diffusion MRI data is avaiblable. 

Given the time course of the summer school, after the initial preprocessing of the data, I will first focus on working with the diffusion MRI data. I believe this data set will allow to first become familiarized with the new neuroimaging tools and create anaylses scripts. When I eventually acquire more data during the rest of my PhD, I will hopefully be able to modify the scripts and work on a larger data set.

![](images/CVI.png)

The figure above is an example of an individual with cortical visual impairment to give you an idea of the type of data, where A) shows a T1-weighted anatomical scan with three different slice views showing the primary visual cortex removal in the left hemisphere and the destruction of the primary visual areas (V1) and B) the individual's visual field showing a symmetric loss across both eyes leading to a complete contralateral visual loss in the right visual field.

As the dataset is not yet open access, feel free to send me a message if you have any questions and I'll be happy to answer!

## Deliverables
At the end of this project I hope to have:
* The current markdown document, completed and revised.
* Jupyter notebook (for data visualization)
* Requirements.txt for the Jupyter notebook

For the course:
* **Week 1 Deliverable:**  [Assessement](https://github.com/mwmaclean/MacLean-M-QLSC612)
* **Week 3 Deliverable:** Data visualization: coming soon!
* **Week 4 Deliverable:** [Presentation](https://github.com/brainhack-school2020/mwmaclean-BHS2020/tree/master/presentation)

### Results

#### Project Deliverable 1:
Organization of MRI data into BIDS format as well as preprocessing the diffusion data with a pipeline in docker

#### Project Deliverable 2:
Tracking diffusion MRI data (preprocessed with deliverable 1) and performing data visualization 

Data visualization: 
1. Interactive correlation matrix with a drop-down for each subject (see image example below)
![](images/correlation_matrix.png)

2. Interactive connectome projected on a 3D glass brain with a drop-down for each subject (see image example below)
![](images/connectome_glassbrain.png)



### Progress overview

This project was initiated by Michèle MacLean May 19th 2020 as part of the BrainHack School. 
Organization of MRI data into BIDS format, preprocessing and basic tracking of the data is complete. Feedback is welcome!

### Tools I learned during this project
* Bash terminal
* GitHub
* Visual Studio Code
* How to implement BIDS using [this tutorial](http://reproducibility.stanford.edu/bids-tutorial-series-part-1b/)
* Python scripts 
* Docker container to run a preprocessing pipeline using [this docker image](https://hub.docker.com/r/gkiar/dwipreproc_fsl-5.0.11_minified)
* [This python scricpt](https://github.com/gkiar/mask2boundary) for creating a seed mask
* DIPY for preprocessing and basic tracking of diffusion weighted images (DWI) using [this docker image](https://hub.docker.com/r/gkiar/dipy_tracking)
* Jupyter Notebook 
* Nilearn, plotly & matplotlib for data visualization
* & More!
 
## Conclusion and acknowledgement
Thanks to the wonderful BrainHack School for this experience as well as all the ressources provided!
Special thanks to my instructors Noor, Benjamin and Greg! 

## References
