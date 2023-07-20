---
layout: project_page
title: X-Ray Occult Carpal Detection
devicename: ScaphX
status: Developing
image: /assets/images/xray_carpel.jpg
sex_graph: /modelcard_demo/assets/images/ScaphX_sex_graph.jpg
ethn_graph: /modelcard_demo/assets/images/ScaphX_ethn_graph.jpg
age_graph: /modelcard_demo/assets/images/ScaphX_age_graph.jpg
summary: ScaphX offers real-time decision support for the detection of scaphoid fractures. The application interprets wrist x-rays to increase the accuracy and confidence of diagnosis, enabling rapid turnaround treatment with discharge or appropriate further management of these patients.
modality: X-ray
model: One line about the model architecture.
pathology: PATHOLOGY
rationale: RATIONALE
patient-pathway: PATHWAY
training-data: Training data was collected using CogStack at GSTT. The clinical reports were read and labelled based on the content of the report. The labels given were as follows:
- Valid: put a 1 if the clinical question (ie the reason for imaging) was scaphoid fracture. If the question is anything else, then put a 0 here. - Valid including other pathology: put a 1 if the clinical question still pertains to a fracture. We want to use these for controls and for expansion of the algorithm later down a line (e.g. so it can detect other fractures). - Fracture: 1 for scaphoid fracture found and 0 for scaphoid fracture not found. 0 also for all other fractures.
All non-valid datasets were eliminated from training set.
train_data_excl: Images with no carpal bones and images with multiple fused views were deleted. Images with poor quality and artefacts were noted but not eliminated from the dataset.
train_input: Images
train_size: 1444
errors: ERRORS
goals: GOALS
success-criteria: CRITERIA

alternatives: <a href="http://www.gleamer.ai/">Gleamer</a>, which specialise in trauma x-rays, has been considered for this purpose but was decided not suitable to solve this particular clinical problem. The decision was made to train an in-house algorithm instead.




---
