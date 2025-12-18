# IEEG-data-preprocessing-and-analysis
Python-based preprocessing and analysis pipelines for iEEG and fMRI data stored in BIDS format, focusing on reproducible signal cleaning and frequency-domain analysis.

utils.py and preprocess_and_analysis.ipynb have been provided. 
'preprocess_and_analysis.ipynb' contains the code for preprocessing and frequency-time analysis for the ieeg data. 
'utils.py' contains some functions and tools that may have been used directly in the main code. 
The zip file provided can be used to actually run the codes according to the correct BIDS path formatting. The code has path-dependent blocks, so it is recommended to use the zip file to get the ready-made structure. As is visible inside the zip folder, 'sub-01' (which is supposed to contain subject data), has been left empty (although the folder structure has been provided inside, but there are no files in there).
This has been done on ethical and moral grounds since subject data cannot be publicly be shared on this platform. 
However, if you wish to run this code yourself, refer to this paper 'https://www.nature.com/articles/s41597-022-01173-0#Sec25' where they have explained the significance of the file structure. Also, here is the actual dataset link : 'https://openneuro.org/datasets/ds003688/versions/1.0.7'. Accordingly, load a subject's full data and change the subject number in the notebook code I have provided. 
