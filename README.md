# seer_breast_cancer

# Goal
The goal was to create a classifying model that is able to take the data of the patient and determine whether the model thinks the patient will survive or not and output how confident it is in such a prediction.

# The Data
The data are from the Kaggle competition [Seer Breast Cancer Data - Labeled]([https://link-url-here.org](https://www.kaggle.com/datasets/reihanenamdari/breast-cancer)), which is based on the SEER Program of the NCI from 2017 November, providing information on population-based cancer statistics. The dataset involved female patients with infiltrating duct and lobular carcinoma breast cancer (SEER primary cites recode NOS histology codes 8522/3) diagnosed in 2006-2010. Patients with unknown tumour size, examined regional LNs, positive regional LNs, and patients whose survival months were less than 1 month were excluded; thus, 4024 patients were ultimately included.
The target variable contains the values 'Alive' and 'Dead'. Any patient that died after the follow-up cut-off in 2017 was recorded to be alive as of the cut-off date. 

The data set consists of the following variables:

TODO: description of every feature.
* Age: Patient age in years.
* Race: Race recode is based on the race variables and the American Indian/Native American IHS link variable. This recode should be used to link to the populations for white, black and other. It is independent of Hispanic ethnicity. For more information, see : http://seer.cancer.gov/seerstat/variables/seer/race_ethnicity.
* Marital Status: This data item identifies the patient’s marital status at the time of diagnosis for the reportable tumor.
* T Stage: Classification of how large the primary tumor is in the breast and what its biomarkers are. For more information see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage/6th.
* N Stage: Classification regarding the tumor spread to the lymph nodes and to, where, what size, and how many lymph nodes are positive. For more information see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage/6th.
* 6th Stage: Stage groups for breast cancer. Doctors assign the stage of the cancer by combining the T, N, and M classifications. For more information see http://seer.cancer.gov/seerstat/variables/seer/ajcc-stage/6th.
* Grade and differentiate: Describes and classifies how well a tumor cell is differentiated. Higher graded tumors have the most abnormal looking cells.
* A Stage: Regional — A neoplasm that has extended 1) beyond the limits of the organ of origin directly into surrounding organs or tissues; 2) into regional lymph nodes by way of the lymphatic system; or 3) by a combination of extension and regional lymph nodes. 
Distant — A neoplasm that has spread to parts of the body remote from the primary tumor either by direct extension or by discontinuous metastasis (e.g., implantation or seeding) to distant organs, issues, or via the lymphatic system to distant lymph nodes.
* Tumor Size: Information on tumor size in millimeters.
* Estrogen Status: Hormone receptor status in cancer cells.
* Progesterone Status: Hormone receptor status in cancer cells.
* Regional Node Examined: Records the total number of regional lymph nodes that were removed and examined by the pathologist.
* Reginol Node Positive: Records the exact number of regional lymph nodes examined by the pathologist that were found to contain metastases. 
* Survival Months: Survival since diagnosis in months.
* Status: ['Alive', 'Dead'] Any patient that dies after the follow-up cut-off date is recoded to be alive as of the cut-off date.


# The Data Processing
TODO: choice of the model, complete pipeline as image

# Metrics
TODO: show final confusion matrix and model results

# Model Interpretation
