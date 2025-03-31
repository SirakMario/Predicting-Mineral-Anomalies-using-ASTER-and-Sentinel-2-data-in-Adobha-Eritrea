# Predicting Mineral Anomalies using ASTER and Sentinel-2 data in Adobha, Eritrea

## Abstract
<p align="justify">
Mineral Prospect Mapping (MPM) plays a major role in identifying economical minerals deposits,
particularly in arid regions with minimal vegetation cover. However, most MPM methods require
extensive geochemical parameters, including multi element analyses and concentration
measurements, making them challenging to implement in resource-constrained regions. This study
proposes an integrated approach combining multispectral remote sensing with machine learning
to predict mineral anomaly zones in Adobha, Eritrea, using limited geochemical parameters. The
proposed approach uses Sentinel-2 and ASTER satellite imagery to detect alteration minerals
through band ratio analysis and RGB color composition. Principal Component Analysis (PCA)
reduces the dimensionality of alteration indices derived from merged RGB composites. Random
Forest (RF) and Support Vector Machine (SVM) classifiers are trained using geochemical data
(Au, Cu, Pb, Zn) combined with the first principal component of each alteration type to predict
anomaly zones across the study area.
The oversampled RF model achieved the highest performance with an F1 score of 0.81 and an
AUC-PR score of 0.74, outperforming other models. The predicted anomaly zones showed strong
spatial correlation with existing traditional (artisanal) mining activities and geophysical survey
results (VTEM), particularly along major fault structures. Iron oxide and phyllic alterations
emerged as the most significant predictors, consistent with the region's geological setting. This
study demonstrates that effective mineral prospecting is possible using limited geochemical
parameters when combined with satellite-derived alteration indices and machine learning. The
methodology offers a cost-effective approach for initial mineral exploration in understudied
regions, providing a practical framework for large-scale prospecting campaigns.
</p>
Keywords: Mineral Prospect mapping (MPM); Random Forest; Support Vector machine;
Anomaly Detection, Multispectral data

## Methodology
[Methology workflow]("https://github.com/SirakMario/Predicting-Mineral-Anomalies-using-ASTER-and-Sentinel-2-data-in-Adobha-Eritrea/blob/main/predictingMinerals.png")
## Result (Predicted Map)
[Methology workflow]("https://github.com/SirakMario/Predicting-Mineral-Anomalies-using-ASTER-and-Sentinel-2-data-in-Adobha-Eritrea/blob/main/results.JPG")
