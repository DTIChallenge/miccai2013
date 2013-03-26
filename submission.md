---
layout: page
title: Submission
group: navigation
description: ""
---
{% include JB/setup %}

## Submission Guidelines

* Participants are invited to submit a zip archive file containing their tractography results for the reconstruction of the left and right corticospinal tract in two neurosurgical cases.
* The results should be submitted as a zip archive 'miccai2013DTIChallenge_firstAuthorName.zip'.
* All results should be in the original DWI image space.
* The tractography results should include 1) the 3D coordinate of the tracts in the VTK-ASCII file format (vtkPolyData), 2) the envelope of the tracts in the ITK-readable Nrrdfile format,  3) a coronal view of the tract overlaid on a FA image in png, and 4) the regions of interest used for the reconstruction in the ITK-readable Nrrdfile format.
* The results should be submitted with the following file naming convention: 
   * patientN_left_tract.vtk
   * patientN_right_tract.vtk
   * patientN_left_env.nhdr & patientN_left_env.raw
   * patientN_right_env.nhdr & patientN_right_env.raw
   * patientN_coronal_view.png
* The paper should include the following elements 1) a presentation of the DTI analysis pipeline, 2) a description of the tractography technique and parameters used, 3) a set of images providing an intuitive way to present the reconstructed tracts to neurosurgeons. Participants are invited to propose an evaluation criteria for their tractography method in the Appendix of the paper.
* Supplementary materials such as short videos, are encouraged, but not mandatory.
* Papers should be formatted in Lecture Notes in Computer Science style. The file format for submission is Adobe Portable Document Format (PDF). Other formats will not be accepted.
* Once you have completed the analysis, upload your workshop paper and results at the location of your choice, and send the url to access them to spujol at bwh.harvard.edu to receive a confirmation of your submission.




