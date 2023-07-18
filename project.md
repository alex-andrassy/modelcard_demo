---
layout: project_page
title: X-Ray Occult Carpal Detection
status: Developing
image: /assets/img/projects/xray_carpel.jpg
csc-lead: test
summary: A computer aided diagnosis tool which would automatically run when a scaphoid fracture is suspected.
modality: X-ray
pathology: Occult carpal fractures (wrist and hands)
rationale: MRI is superior in identification of occult carpal fracture, but is not always accessible. An AI tool to aide clinical diagnosis of occult carpal fractures using x-rays would increase diagnostic sensitivity in areas and situations where MRI is not available.
patient-pathway: A&E attendance with a suspected scaphoid fracture or hand/wrist injury.
training-data: Patient cohort identified using CogStack looking for phrases 'scaphoid' and 'MRI clinical'. The query generated a list of approximately 1000 patients who have had an MRI, with the view that all patients who had an MRI will also have had an x-ray. The patient list is now being stratified to `test`, `control` and `back-up` groups.
errors: Needless referrals to fracture clinic and needless immobilisation in patients who do not have a fracture; repeated x-rays; referrals to MRI.
goals: An automated computer aided diagnosis tool triggered when appropriate x-rays are taken.
success-criteria: Improvement in diagnostic accuracy and diagnostic speed.
alternatives: <a href="http://www.gleamer.ai/">Gleamer</a>, which specialise in trauma x-rays, has been considered for this purpose but was decided not suitable to solve this particular clinical problem. The decision was made to train an in-house algorithm instead
---
text