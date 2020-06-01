# mwmaclean-BHS2020
This project is part of the Brainhack School 2020

Team contributors: Michèle MacLean & Brainhack School members

![BrainHack School](bhs2020.png)

## Summary 

Hello! I'm currently a PhD student in Cognitive Neuroscience at l'Université de Montréal. My main focus is to study cortical visual impairment using MRI techniques. Damage to the primary visual areas can result in clinical blindness and prompt a cascade of dynamical structural and functional alterations of the neural networks at both the cortical and subcortical level. Following this damage, individuals can sometimes preserve the ability to non consciously process visual information in their blind field, a striking phenomenon know as blindsight. My fascination resides in understanding how the brain can process visual information without conscious awareness.

The overall goal of the current project is to become more proficient with tools to organize, analyze and visualize MRI data learned during the BrainHack Summer School. I'm very interested in working with a team or perhaps joining projects if possible (i.e. feel free to send me a message if you are working with diffusion MRI, resting state functional connectivity or fMRI)! 


## Project definition 

### Background

This project will investigate the consequences of a primary visual cortex lesion on cerebral reorganization using magnetic resonance imaging, in particular diffusion MRI and/or resting state functional connectivity. For this, I will use previously acquired data from l'Unité de Neuroimagerie Fonctionnelle in Montréal. 

The following objectives represent the next planned steps: 
The first steps will be to try to 1) organize the MRI data in a BIDS friendly format and then 2) preprocess the data. Then, I plan to explore 3) analyzing diffusion MRI (i.e. dwi tracking) and 4) perform data visualization.

### Tools 
This project will rely on the following:
* GitHub for creating a repository & assembling all the resources.
* BIDS as a standard to organize the neuroimaging data
* MRIcroGL to convert dicom files to nifti
* Python 
* DIPY for preprocessing and basic tracking of diffusion weighted images (DWI)
* Docker container to run preprocessing pipeline
* Jupyter Notebook to document the process and for data visualization
* Data visualization tools (e.g. Numpy, Matplotlib, Seaborn).


### Data 
MRI data was acquired with a high resolution 3 Tesla scanner (Siemens Trio system) and consists of a preliminary data set of 5 subjects, including 1 individual with cortical visual impairment with blindsight and 4 neurotypical controls. For each participant, raw structural MRI, resting state functional connectivity, fMRI and diffusion MRI data is avaiblable. 

Given the time course of the summer school, after the initial preprocessing of the data, I will first focus on working with the diffusion MRI data. I believe this data set will allow to first become familiarized with the new neuroimaging tools and create anaylses scripts. When I eventually acquire more data during the rest of my PhD, I will hopefully be able to modify the scripts and work on a larger data set.

![](CVI.png)

The figure above is an example of an individual with cortical visual impairment to give you an idea of the type of data, where A) shows a T1-weighted anatomical scan with three different slice views showing the primary visual cortex removal in the left hemisphere and the destruction of the primary visual areas (V1) and B) the individual's visual field showing a symmetric loss across both eyes leading to a complete contralateral visual loss in the right visual field.



### Deliverables
At the end of this project I hope to have:
* The current markdown document, completed and revised.
* Python script for the main analyses 
* Jupyter notebook (including explanations)
* Data visualization graphs
* Requirements.txt



## Results 
#### Deliverable 1: report 
Organization of MRI data into BIDS format as well as preprocessing the diffusion data with a pipeline in docker

#### Deliverable 2: TBD
Coming soon!

### Progress overview

The project was initiated by Michèle MacLean May 19th 2020 as part of the BrainHack School. Feedback is welcome!

### Tools I learned during this project
* Bash terminal
* GitHub
* How to implement BIDS
* MRIcroGL
* Python 
* Docker container to run a preprocessing pipeline using ['this docker image'](https://hub.docker.com/r/gkiar/dwipreproc_fsl-5.0.11_minified)
* DIPY for preprocessing and basic tracking of diffusion weighted images (DWI)
* Jupyter Notebook 
* More coming soon!
 
## Conclusion and acknowledgement
Thanks to the wonderful BrainHack School!
