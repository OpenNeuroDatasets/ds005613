# README

The README is the starting point for researchers using NEBULA101.

## Details Related to Access to the Data

- **Data User Agreement**:  Data are publicly available under CC0 license and fully anonymised.

- **Contact Person**: 
  - **Name**: Alessandra Rampinini, PhD
  - **Email**: alessandra.rampinini@unige.ch
  - **ORCID**: 0000-0002-3016-5231

## Overview

- **Project Name**: NEBULA101 - NeuroBehavioural Understanding of Language Aptitude
- **Year(s) that the Project Ran**: 2020-2024

The project aimed to investigate the behavioural and neural correlates of language aptitude and their relationship with brain structure and function. The experiment included various tasks that participants completed to evaluate their cognitive and linguistic abilities as well as neuroimaging data (structural and functional).

- **Description of the Contents of the Dataset**: 
  The dataset contains behavioral and neural assessments for 101 participants, structured according to the BIDS standard. It includes a `dataset_description.json` file summarizing the data.

- **Quality Assessment of the Data**: 
  The quality of the data was assessed using descriptive statistics and various automated methods for MRI QC, revealing a high completion rate with minimal missing data, acceptable to good internal consistency and distribution for the behavioural data, and acceptable quality metrics for the MRI data. For a comprehensive view of quality assessment, refer to /code/validation, where all code run to quality assess the data is stored, and derivatives/validation, where its results are stored.

## Methods

### Subjects

The final sample includes 101 individuals (Mage= 23.35 years SD = 4.08, 68F, Meducation= 15.34 years, SD = 2.35)

- **Information about the Recruitment Procedure**: Participants were recruited through flyers and advertisements in Geneva, Switzerland, and neighbouring France or francophone cantons.
- **Subject Inclusion Criteria**: healthy adults without previous neurological or psychiatric diagnosis.
- **Subject Exclusion Criteria**: Participants with neurological disorders or severe psychiatric conditions were excluded, as well as those  with chronic illnesses or past history of cancer or autoimmune diseases requiring invasive treatment. Participants with dyslexia and hyperpolyglots (speaking more than 10 languages with a self-reported proficiency higher than 4 out of 6) were not included in this release.

### Apparatus

The experiment was conducted in 4 subsequent sessions: one online unsupervised session for questionnaire collection, one online supervised behavioural session, one in-person behavioural session and one imaging session.

### Task Organization


- **Task Order**: The order of tasks was pseudo-randomised across participants to mitigate order effects (15 possible task orders).
- **Other Activities**: Breaks were provided between tasks  and halfway through the imaging session to minimise fatigue.


### Experimental Location

The study was conducted at the Human Neuroscience Platform, Campus Biotech, located in Geneva, Switzerland. 

### Missing Data

Some participants had incomplete responses due to time constraints or misunderstanding of the questions. A log of missing data is maintained for reference in /derivatives/validation/data_checks/

### Notes

Any additional information regarding the data acquisition process is available in the article describing the NEBULA101 dataset. 