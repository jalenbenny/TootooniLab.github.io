---
layout: page
title: Research
permalink: /research/
---

## AI IN DRUG DOSING DECISION MAKING IN CRITICAL CARE​
Vancomycin is an antibiotic used to treat infections caused by bacteria. A prescription is required to obtain the medication and cannot be bought over the counter. Prescribing too high of a dosage can cause harm to the kidneys or ears, which will result in longer hospital stays as well as higher mortality rates. Too low of a dosage may cause a antimicrobial resistance towards the medication, rendering the medicine useless towards the patient which can double the chances of developing a serious health condition and triples the chance of death. In this project, we collaborate with scholars from Mayo Clinic, Loyola University Chicago, University of Illinois Chicago, and University of Chicago and use their data to advance Artificial Intelligence (AI) Models to identify and design a plan for the correct dosage which then gets translated and sent to pharmacists and physicians to use. 
![1stimage](https://github.com/TootooniLab/TootooniLab.github.io/assets/137564862/ffd0ebb6-167e-416d-815a-df393bbbbffc)
<br>
## AI IN EARLY DETECTION OF EVENTS​
When a patient enters the emergency room, an assessment known as a triage must be done ​​to determine the severity of the need for treatment. After the deposition decision, a bed must be assigned to the patient which is where they will be stationed until the end of their visit. Ideally, the hospital admission process can be predicted so that the bed coordination can begin before the patient enters the ER, thus time is saved for the patient to be admitted. Our lab uses the chief complaints, given by the patient upon first arrival, which is submitted into Natural Language Processing (NLP) models to extract the concepts in the form of SNOMED-CT codes called SCTIDs. SCTIDs will then be mapped into CC groups which can be used on their own or be used in downstream processes such as resource allocation and clinical decision support.
![2ndimage](https://github.com/TootooniLab/TootooniLab.github.io/assets/137564862/b76984ca-d3b8-43a8-8c5c-e76e8e680bb3)
<br>
## HEALTH DISPARITIES IN HYPERTENSION CONTROL​​
This project analyzes possible influencing factors related to therapeutic inertia in hypertensive patients. Patients may experience varying quality of healthcare depending not only on patient demographic features, but also on geospatial socioeconomic characteristics. Through the combination of Electronic Health Record and Census data, we can examine the influence of various geospatial features on therapeutic inertia. The Area Deprivation Index (ADI), along with its 17 predictors, can be used for this analysis. While this allows us to provide further insight into the complicated concept of therapeutic inertia, it is difficult to determine appropriateness of therapeutic inertia.The analysis of progress notes through Large Language Models (LLMs) may provide the needed context to distinguish between appropriate and inappropriate therapeutic inertia 
![image3](https://github.com/TootooniLab/TootooniLab.github.io/assets/137564862/9b29fce2-fd1e-48f4-84b6-ab66b25d60a1)
![image4](https://github.com/TootooniLab/TootooniLab.github.io/assets/137564862/73cfed7b-66d8-41eb-8b4d-b97db7ad58a8)
<br>
## SHIELD ILLINOIS​​
The SHIELD Illinois program was created to prevent COVID transmission and provide testing to communities in Illinois. It's impact on underrepresented populations and potential for guiding future pandemic response efforts however, require further investigation. Data from the SHIELD Illinois program, the Chicago Department of Public Health, and electronic health records from two major health centers in the Chicagoland area will be used alongside the COVID Community Vulnerability Index (CCVI) and the Area Deprivation Index (ADI) to determine how underrepresented communities benefit from the program. Our objective is to evaluate the effect of the SHIELD testing program on COVID severe outcomes such as admission to Intensive Care Unit (ICU), mechanical ventilation use, and death. Artificial Intelligence (AI) is then used to identify the most effective attributes related to the location of testing centers on the volume of the performed tests, which will provide guidance for future pandemic response planning. 
![image5](https://github.com/TootooniLab/TootooniLab.github.io/blob/master/images/image5.png?raw=true)
<br>
Image from University of Illinois System

## ECG AI RESEARCH​​
The United States has over 6 million adults suffering from heart failure, a condition with a high mortality rate and decreased quality of life. Early recognition and timely interventions are essential to reduce the risk of heart failure on individuals and the healthcare system as a whole. However, more than half of heart failure patients have preserved left ventricular ejection fraction (HFpEF), and current treatments mostly target reduced left ventricular ejection fraction (HFrEF). HFpEF is a heterogeneous syndrome with an unclear etiology, meaning that there are many causes for HFpEF and yet the causes are unclear. The goal of this project is to use artificial intelligence (AI) and electrocardiogram (ECG) data to predict incident HFpEF risk and subtype prevalent HFpEF in a cost-effective and accessible manner.
<br>
![image6](https://github.com/TootooniLab/TootooniLab.github.io/blob/master/images/image6.jpeg?raw=true)
<br>
Picture from Journal of Molecular and Cellular Cardiology

## PREHOSPITAL STROKE TRIAGE
When a stroke occurs, minutes matter. Paramedics in the field need a fast, reliable way to recognize a stroke in progress and route the patient to the right level of care before they ever reach a hospital door. This project develops and validates machine learning models on emergency medical services (EMS) data to predict stroke and severe stroke events at the point of first contact. The work goes beyond the model itself, including a workflow and implementation study built alongside paramedics and clinicians, along with a study examining how paramedics themselves perceive and trust an ML-based triage tool in practice.
<br>

## ECONOMIC BURDEN OF STROKE MIS-TRIAGE
Not every stroke patient ends up at the hospital best equipped to treat them. When a patient is mis-triaged, sent to a non-specialized hospital instead of a comprehensive stroke center, the clinical and financial costs can be substantial. This project uses nationwide emergency department data (HCUP) to quantify the scale of that burden, examining how often mis-triage occurs and what it costs patients and the healthcare system in retrospective analysis.
<br>

## TOPIC MODELING OF STROKE TRIAGE PATTERNS
Working alongside the mis-triage research above, this project applies topic modeling to clinical data to surface recurring patterns in how stroke patients are triaged, and where mis-triage tends to occur. The goal is to give the broader stroke triage work a clearer picture of the patterns hiding in the data.
<br>

## CLINICAL CONCEPT EXTRACTION FROM EHR
Electronic health records hold most of a patient's clinical picture in free text rather than structured fields, which makes that information hard to search, compare, or feed into downstream models. This project uses Spark NLP to perform clinical concept extraction and chunk detection directly from EHR text, turning unstructured notes into usable, structured clinical concepts.
<br>

## AI-AS-A-JUDGE FOR HEALTHCARE AI SYSTEMS
As more AI tools make their way into clinical workflows, someone has to answer a harder question: how do we know if the AI itself is working well, and working safely? This project builds an AI-as-a-Judge framework designed to evaluate and validate the performance, reliability, and safety of AI systems before and after they're deployed in healthcare settings.
<br>

## SCHEMA-GUIDED CLINICAL INFORMATION EXTRACTION
Nursing documentation is dense, fast-written, and highly variable in structure, which makes it difficult to extract consistent, structured information at scale. This project combines a hybrid dense and BM25 retrieval system with a large language model verification stage to pull schema-guided clinical information out of nursing dictations. The work was developed for the MEDIQA-SYNUR 2026 shared task.
<br>

## MULTIMODAL CLINICAL OUTCOME MODELING
Patient outcomes rarely depend on just one type of data. This project builds an end-to-end multimodal fusion pipeline on the MIMIC-IV dataset to predict 30-day post-discharge mortality, comparing early, intermediate, and late fusion strategies for combining structured EHR data with clinical notes. The pipeline draws on a range of models, including TabPFN, XGBoost, and BioClinical-ModernBERT, alongside a LoRA fine-tuned Llama-3 combined through adapter merging.
<br>

## KNOWLEDGE GRAPH-ENHANCED LLM REASONING
Large language models are good at generating fluent answers, but not always grounded ones, especially when reasoning about how a drug, disease, and gene relate to one another. This project integrates the PrimeKG biomedical knowledge graph with large language models to see whether structured graph context can improve the accuracy of that reasoning.
<br>

## AKI STAGING AND BASELINE CREATININE ESTIMATION
Diagnosing acute kidney injury (AKI) accurately depends on knowing a patient's baseline kidney function, which isn't always known and often has to be estimated. This project builds an AKI staging detection pipeline based on KDIGO criteria, comparing baseline serum creatinine back-calculation methods, CKD-EPI 2021 and MDRD, across a range of clinical scenarios to identify the most reliable approach.
<br>

## FORECASTING INFLUENZA-LIKE ILLNESS
Public health teams can respond faster to a flu outbreak if they can see it coming. This project trains a Transformer model to forecast Influenza-Like Illness (ILI) cases from over 50,000 weekly records, cutting forecast error (RMSE) by 63 percent compared to a traditional ARIMA approach and outperforming LSTM models on long-term temporal patterns, supporting earlier outbreak detection and intervention.
<br>

## EYE MOVEMENT ANALYSIS FOR PARKINSON'S DIAGNOSIS
Parkinson's disease affects how the eyes move long before many other symptoms become obvious, which opens the door to earlier, non-invasive diagnosis. This project uses a computer vision pipeline to analyze eye-tracking video and extract clinical biomarkers, such as saccade velocity, that can support quantitative, scalable assessment of ocular motor behavior in clinical decision-making.
<br>

## EVALUATING AI VISUALIZATION TOOLS IN HEALTHCARE RESEARCH
As AI-generated charts and visualizations become easier to produce, it's worth asking whether they can be trusted in academic and clinical research settings. This project assesses a range of AI platforms on their ability to generate accurate, clear, and effective visualizations, examining their strengths, limitations, usability, and risks in order to identify best practices for responsible use.
<br>
