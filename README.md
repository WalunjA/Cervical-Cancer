# Cervical Cancer Detection

## Objective
---
<p>
Cervical cancer is so easy to prevent if caught in its pre-cancerous stage that every woman should have access to effective, life-saving treatment no matter where they live. Today, women worldwide in low-resource settings are benefiting from programs where cancer is identified and treated in a single visit. However, due in part to lacking expertise in the field, one of the greatest challenges of these cervical cancer screen and treat programs is determining the appropriate method of treatment which can vary depending on patients’ physiological differences.


Especially in rural parts of the world, many women at high risk for cervical cancer are receiving treatment that will not work for them due to the position of their cervix. This is a tragedy: health providers are able to identify high risk patients, but may not have the skills to reliably discern which treatment which will prevent cancer in these women. Even worse, applying the wrong treatment has a high cost. A treatment which works effectively for one woman may obscure future cancerous growth in another woman, greatly increasing health risks.

This project tried to develop a basic algorithm which accurately identifies a woman’s cervix type based on images. Doing so will prevent ineffectual treatments and allow healthcare providers to give proper referral for cases that require more advanced treatment.
</p>

## Dataset
---

The Dataset is presented by Intel and MobileODT via Kaggle

[Link to the Dataset](https://www.kaggle.com/c/intel-mobileodt-cervical-cancer-screening/data)

## Files
---

- Cervical_Cancer.ipynb - IPython Notebook of the solution
- Cervical_Cancer.py - Simple Python file of the Solution
- data.npz - Dataset of the embedding vectors
- predictions.csv - The CSV file where the algorithm saves it's Output
- weights.h5 - Trained Neural Net Weights


## Program Flow
---

Cervical_Cancer.py --> Convert Images to embedding vectors --> Feed the Flattened Vectors into Nerual Net Model --> Output will be stored in prediction.csv


## Instructions
---
### To run the program follow the following instructions

- Install the packages in requirements.txt by running `pip install -r requirements.txt`

- Download the images via the Link to the Dataset given above and store the Test Images inside the test folder and the Training Images in the training folder

- Simply run Cervical_Cancer.py

- The output will be stored in predictions.csv


