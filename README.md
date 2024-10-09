# my-ml-bio-project

This project focuses on applying machine learning techniques in the field of bioinformatics to aid in drug discovery. The project involves collecting and preprocessing bioactivity data from the ChEMBL database, as well as the computation of molecular descriptors using the Padel Descriptor software. The collected dataset is then used to build regression models for predicting the potency of compounds against a target protein, specifically acetylcholine esterase.

## Features

- __Data Collection:__ The project demonstrates how to retrieve bioactivity data from the ChEMBL database using Python, utilizing the ChEMBL web resource client library.
- __Data Preprocessing:__ The collected bioactivity data is preprocessed to handle missing values, label compounds, and calculate molecular descriptors.
- __Exploratory Data Analysis:__ The project covers exploratory data analysis techniques using visualizations and statistical analysis, providing insights into the dataset.
- __Model Building:__ Several machine learning algorithms, such as Random Forest, are built and compared for their predictive performance using the lazy predict library.

## Tools & Libraries

- __Pandas:__ Data manipulation and analysis.
- __Scikit-learn:__ The library is used for machine learning tasks, including model building and evaluation.
- __Padel Descriptor:__ A software used for calculating molecular descriptors based on the provided SMILES notation of compounds.
- __Seaborn and Matplotlib:__ These libraries are used for data visualization.
