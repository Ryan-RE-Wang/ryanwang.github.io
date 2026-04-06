---
title: "AI recognition of patient race in medical imaging: a modelling study"
collection: publications
category: manuscripts
permalink: /publication/2022-06-01-reading-race
excerpt: 'We identified that the AI models could differentiate the demographic attributes of patients even after augmentation, which posting an enormous risk for all model deployments in medical imaging'
date: 2022-06-01
venue: 'The Lancet Digital Health'
paperurl: 'https://academicpages.github.io/files/paper3.pdf'
---

**Background** Previous studies in medical imaging have shown disparate abilities of artificial intelligence (AI) to detect a person’s race, yet there is no known correlation for race on medical imaging that would be obvious to human experts when interpreting the images. We aimed to conduct a comprehensive evaluation of the ability of AI to recognise a patient’s racial identity from medical images. 

**Methods** Using private (Emory CXR, Emory Chest CT, Emory Cervical Spine, and Emory Mammogram) and public (MIMIC-CXR, CheXpert, National Lung Cancer Screening Trial, RSNA Pulmonary Embolism CT, and Digital Hand Atlas) datasets, we evaluated, first, performance quantification of deep learning models in detecting race from medical images, including the ability of these models to generalise to external environments and across multiple imaging modalities. Second, we assessed possible confounding of anatomic and phenotypic population features by assessing the ability of these hypothesised confounders to detect race in isolation using regression models, and by re-evaluating the deep learning models by testing them on datasets stratified by these hypothesised confounding variables. Last, by exploring the effect of image corruptions on model performance, we investigated the underlying mechanism by which AI models can recognise race. 

**Findings** In our study, we show that standard AI deep learning models can be trained to predict race from medical images with high performance across multiple imaging modalities, which was sustained under external validation conditions (x-ray imaging [area under the receiver operating characteristics curve (AUC) range 0·91–0·99], CT chest imaging [0·87–0·96], and mammography [0·81]). We also showed that this detection is not due to proxies or imagingrelated surrogate covariates for race (eg, performance of possible confounders: body-mass index [AUC 0·55], disease distribution [0·61], and breast density [0·61]). Finally, we provide evidence to show that the ability of AI deep learning models persisted over all anatomical regions and frequency spectrums of the images, suggesting the efforts to control this behaviour when it is undesirable will be challenging and demand further study. 

**Interpretation** The results from our study emphasise that the ability of AI deep learning models to predict self-reported race is itself not the issue of importance. However, our finding that AI can accurately predict self-reported race, even from corrupted, cropped, and noised medical images, often when clinical experts cannot, creates an enormous risk for all model deployments in medical imaging. Funding National Institute of Biomedical Imaging and Bioengineering, MIDRC grant of National Institutes of Health, US National Science Foundation, National Library of Medicine of the National Institutes of Health, and Taiwan Ministry of Science and Technology.
