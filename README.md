# RS-fetMRI
RS-FetfMRI for processing Fetal resting-state functional MRI scans
# Usage
The RS-FetMRI package consists of several components, including a main script named 'RSFetfMRI.m,' which is divided into six modules (as shown in Figure 1). Additionally, there is a custom MATLAB function called 'Create_template.m' and a modified version of the Artifact Detection Tool, referred to as 'art.m,' along with corresponding configuration files. The RS-FetMRI script relies on various SPM functions for image processing and visualization. Furthermore, it includes a directory named 'Templates,' which contains three subfolders ('Template_for_session,' 'Template_Priors_Seg,' and 'Template_orig') containing different Nifti files used for the first-pass masking, segmentation, and visualization. Specifically, as outlined in the 'Installation and Requirements' section, it is necessary to download the 'Template_orig' files from a separate website.
# Requirement
* Matlab2013 (or above);
* SPM12 (or above);
# TestSet
The RS-FetMRI package also includes a complete Test Set. The subject under examination was at the 35 GW.All the images present in this manual were selected from this subject. If the user would like to try the analysis on this subject, simply download the material and then the user should move all of the folders regarding M2 to M6 into a different repository. Please note that initialization is required to try the TestSet. All of the parameters inserted during the processing are reported in the supplementary TestSet parameters.
