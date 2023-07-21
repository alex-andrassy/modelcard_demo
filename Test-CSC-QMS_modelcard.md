---
layout: project_page
title: X-Ray Occult Carpal Detection
devicename: ScaphX
status: Developing
image: /assets/images/xray_carpel.jpg
sex_graph: /modelcard_demo/assets/images/ScaphX_sex_graph.png
ethn_graph: /modelcard_demo/assets/images/ScaphX_ethn_graph.png
age_graph: /modelcard_demo/assets/images/ScaphX_age_graph.png
summary: ScaphX offers real-time decision support for the detection of scaphoid fractures. The application interprets wrist x-rays to increase the accuracy and confidence of diagnosis, enabling rapid turnaround treatment with discharge or appropriate further management of these patients.
modality: X-ray
model: U-net
pathology: PATHOLOGY
rationale: RATIONALE
patient-pathway: PATHWAY
training-data: Training data was collected using CogStack at GSTT.
train_data_excl: Images with no carpal bones and images with multiple fused views were deleted. Images with poor quality and artefacts were noted but not eliminated from the dataset.
train_input: Images
train_size: 1444
errors: ERRORS
goals: GOALS
success-criteria: CRITERIA

alternatives: <a href="http://www.gleamer.ai/">Gleamer</a>, which specialise in trauma x-rays, has been considered for this purpose but was decided not suitable to solve this particular clinical problem. The decision was made to train an in-house algorithm instead.




---
