---
title: "Predictive Time-Series Analysis of Single-Qubit Quantum Circuit Outcomes for a Superconducting Quantum Computer: Forecasting Error Patterns"
collection: publications
permalink: /publications/quantum_timeseries_prediction_1
excerpt: In this work, we analyze and predict the output patterns of a single qubit quantum circuit by treating the results of repeated executions as a time series. Specifically, we collect measurement data from multiple runs of a quantum circuit and construct a time series from these observations. By training a predictive model, we aim to forecast future outcomes, providing insights into the error behavior of the quantum circuit. Additionally, we analyze time series data from two different circuits executed on the same qubit to investigate potential relationships and assess whether one dataset can be used to predict the other. Our findings reveal key characteristics of quantum circuit outputs, including stationarity, autocorrelation, seasonality, trends, linearity, and causality. The analysis highlights intriguing behaviors within the dataset. Furthermore, we evaluate multiple time series prediction methods and determine that XGBoost (Extreme Gradient Boosting) outperforms other approaches, demonstrating its effectiveness in accurately predicting quantum computing outputs in subsequent runs."
date: 2025-02-27
venue: 'IEEE ACCESS'
short: 'IEEE ACCESS'
paperurl: 'https://inspirehep.net/files/8cf076ce2dd33d1ba5187699a6358261'
teaser: '../images/ft.jpeg'
authors:  <b>Saba Tabatabaee</b>, Jing Liu, Carol Espy-Wilson"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
redirect_from: 
  - /ft
---

<p style="text-align:center;">
<img src="../images/ft.jpeg" width="800">
</p>

## Abstract
<div style="text-align: justify"> Creating Speaker Verification (SV) systems for classroom settings that are robust to classroom noises such as babble noise is crucial for the development of AI tools that assist educational
environments. In this work, we study the efficacy of finetuning with augmented children datasets to adapt the x-vector and ECAPA-TDNN to classroom environments. We demonstrate that finetuning with augmented children’s datasets is powerful in that regard and reduces the Equal Error Rate (EER) of xvector and ECAPA-TDNN models for both classroom datasets and children speech datasets. Notably, this method reduces EER of the ECAPA-TDNN model on average by half (a 5% improvement) for classrooms in the MPT dataset compared to the ECAPA-TDNN baseline model. The x-vector model shows an 8% average improvement for classrooms in the NCTE dataset compared to its baseline.</div>
<br>

| Paper                                         
|---------------------------------------------------------------------------------------------------------|
| [**FT-Boosted**](https://www.isca-archive.org/interspeech_2025/tabatabaee25_interspeech.pdf) |

<br>

Please cite our work if you found it useful,

```
@inproceedings{tabatabaee25_interspeech,
  title     = {{FT-Boosted SV: Towards Noise Robust Speaker Verification for English Speaking Classroom Environments }},
  author    = {Saba Tabatabaee and Jing Liu and Carol Espy-Wilson},
  year      = {2025},
  booktitle = {{Interspeech 2025}},
  pages     = {2815--2819},
  doi       = {10.21437/Interspeech.2025-1002},
  issn      = {2958-1796},
}
```
