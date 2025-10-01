---
title: "Predictive Time-Series Analysis of Single-Qubit Quantum Circuit Outcomes for a Superconducting Quantum Computer: Forecasting Error Patterns"
collection: publications
permalink: /publications/quantum_timeseries_prediction
excerpt: " In this work, we analyze and predict the output patterns of a single qubit quantum circuit by treating the results of repeated executions as a time series. Specifically, we collect measurement data from multiple runs of a quantum circuit and construct a time series from these observations. By training a predictive model, we aim to forecast future outcomes, providing insights into the error behavior of the quantum circuit. Additionally, we analyze time series data from two different circuits executed on the same qubit to investigate potential relationships and assess whether one dataset can be used to predict the other. Our findings reveal key characteristics of quantum circuit outputs, including stationarity, autocorrelation, seasonality, trends, linearity, and causality. The analysis highlights intriguing behaviors within the dataset. Furthermore, we evaluate multiple time series prediction methods and determine that XGBoost (Extreme Gradient Boosting) outperforms other approaches, demonstrating its effectiveness in accurately predicting quantum computing outputs in subsequent runs."
date: 02-27-2025
venue: 'IEEE ACCESS'
short: ''
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10906565'
teaser: '../images/quantum.png'
authors:  <b>Mohammadreza Saghafi</b>, Lamine Mili"
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'



## Abstract
<div style="text-align: justify"> Quantum computing promises a paradigm shift in computational power. However, a major challenge is mitigating the inherent noise and errors in quantum circuits. As quantum computers operate, their fragile qubits are highly susceptible to environmental disturbances, leading to errors that affect the outcomes of repeated circuit executions. Understanding and predicting these errors is crucial for improving the accuracy and reliability of quantum computing systems. In this work, we analyze and predict the output patterns of a single qubit quantum circuit by treating the results of repeated executions as a time series. Specifically, we collect measurement data from multiple runs of a quantum circuit and construct a time series from these observations. By training a predictive model, we aim to forecast future outcomes, providing insights into the error behavior of the quantum circuit. Additionally, we analyze time series data from two different circuits executed on the same qubit to investigate potential relationships and assess whether one dataset can be used to predict the other. Our findings reveal key characteristics of quantum circuit outputs, including stationarity, autocorrelation, seasonality, trends, linearity, and causality. The analysis highlights intriguing behaviors within the dataset. Furthermore, we evaluate multiple time series prediction methods and determine that XGBoost (Extreme Gradient Boosting) outperforms other approaches, demonstrating its effectiveness in accurately predicting quantum computing outputs in subsequent runs.</div>
<br>

| Paper                                         
|---------------------------------------------------------------------------------------------------------|
| [**Speech Inversion by Incorporating Nasality**](https://arxiv.org/pdf/2506.09231) |

<br>

Please cite our work if you found it useful,

```
@ARTICLE{10906565,
  author={Saghafi, Mohammadreza and Mili, Lamine},
  journal={IEEE Access}, 
  title={Predictive Time-Series Analysis of Single-Qubit Quantum Circuit Outcomes for a Superconducting Quantum Computer: Forecasting Error Patterns}, 
  year={2025},
  volume={13},
  number={},
  pages={40115-40132},
  keywords={Time series analysis;Integrated circuit modeling;Quantum circuit;Forecasting;Predictive models;Noise;Data models;Computational modeling;Prevention and mitigation;Computers;Quantum computing;quantum error mitigation;time series analysis;predictive modeling;XGBoost},
  doi={10.1109/ACCESS.2025.3546259}}
```
