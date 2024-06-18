# Causal Discovery for Time Series Datasets with Partially Overlapping Variables

![problem-def-2](https://github.com/AdeLouis/KR2024-Time-Series-Causal-Discovery/assets/17919698/f98202fd-32dd-4526-bb1d-955876bc9c69)


**Motivation**: One of the vital challenges for causal discovery in health is that different variables are measured for each patient, as measurements depend on a patient’s health status and treatment. Existing methods to address this problem focus on non-temporal data and hence do not consider the time lags between relationships, which are critical to know when creating effective interventions. 

*To address this problem, we make the key observation that while a variable may be missing for one patient, it may be measured for others. Thus, we leverage the fact that variable sets between patients often partially overlap. We propose an iterative approach that combines causal models when they are structurally equivalent by correcting for errors in causal relationships due to missing observations and reconstructing missing variables.*

Gomez, L.A., Claassen, J., and Kleinberg, S. Causal Inference for Time Series Datasets with Partially Overlapping Variables. Knowledge Representation 2024 (in submission)
