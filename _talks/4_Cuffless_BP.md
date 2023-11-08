---
title: "Cuffless Blood Pressure Estimation using PPG and ECG"
collection: talks
type: "Research Assistant"
permalink: /talks/4_Cuffless_BP
venue: "Supervisor: Prof. ZHANG Yuanting(张元亭)"
date: 2023-01-24
location: "HK COCHE"
---

This research marked a significant milestone in my transition from Nursing to Biostatistics, as it introduced me to the world of **signal processing** and **machine learning** for **disease estimation**. I am deeply grateful to Prof. ZHANG for his invaluable guidance and patience throughout this project. My work during this period encompassed three main components:
1. **Replicating Research on Blood Pressure Estimation**: In this part, I focused on replicating a paper that used machine learning models to estimate blood pressure (BP) based on photoplethysmogram (PPG) and electrocardiogram (ECG) signals. My tasks included:
   * **Data Preprocessing**: I worked with a dataset of 600 patients from the MIMIC-II database.
   * **Feature Extraction**: I extracted 13 essential features from the PPG and ECG signals, including pulse transit time (PTT), various amplitudes (T-wave, Q-wave, R-peak, S-peak, Low-peak), QRS intervals, R to low-peak amplitudes, R-peak intervals, PPG pulse amplitude, PPG pulse width, PPG high to low interval, and PPG slope change standard deviation.
   * **Machine Learning Models**: I applied several machine learning models in BP estimation, including Long Short-Term Memory (LSTM), Gated Recurrent Unit (GRU), Random Forest (RF), and Linear Models. Notably, the LSTM model outperformed the others.
2. **Investigating the Relationship Between PPG, ECG, Reference BP, and Estimated BP**:
   * I utilized LSTM and Random Forest (RF) models for estimating blood pressure waveforms.
   * I calculated the correlation coefficient (CC) for Reference BP & Estimated BP, PPG & Estimated BP, and ECG & Estimated BP.
   * [Result](https://yanweijin.github.io/images/ccmae.png):
3. **Optimal Feature Set for Blood Pressure Estimation**:
   * I Conducted a review of a published article: [Beat-to-beat continuous blood pressure estimation with optimal feature set of PPG and ECG signals using deep recurrent neural networks](https://www.oaepublish.com/articles/2574-1209.2023.30).
   * I performed statistical analyses in this article.
