# Awesome PPG(Photoplethysmography)


![Awesome](https://awesome.re/badge.svg) ![GitHub stars](https://img.shields.io/github/stars/mintisan/awesome-ppg.svg?style=social)

A curated list of awesome libraries, datasets, tutorials, papers, and other resources related to Photoplethysmography(PPG) analysis. This repository aims to be a comprehensive and organized collection that will help researchers and developers in the world of PPG!

## Table of Contents

- [Standard](#standard)
- [Library](#library)
- [Papers](#papers)
- [Books](#books)
- [Datasets](#datasets)
- [Tutorial](#tutorial)
- [Datasets](#datasets)
- [Contributing](#contributing)

## Standard


## Library

- [HeartPy](https://github.com/paulvangentcom/heartrate_analysis_python) : Python Heart Rate Analysis Package, for both PPG and ECG signals
- [Neurokit](https://github.com/neuropsychology/NeuroKit) : The Python Toolbox for Neurophysiological Signal Processing
- [PPG-Beats](https://ppg-beats.readthedocs.io/en/latest/)



### Comparison


## Papers

### Review

- 2022-[Photoplethysmography Signal Processing and Synthesis](https://peterhcharlton.github.io/publication/ppg_sig_proc_chapter/PPG_sig_proc_Chapter_20210612.pdf)-34
- 2023-[Photoplethysmography in Wearable Devices: A Comprehensive Review of Technological Advances, Current Challenges, and Future Directions](https://www.mdpi.com/2079-9292/12/13/2923)-2
- 2023-[The 2023 wearable photoplethysmography roadmap](https://pure.coventry.ac.uk/ws/portalfiles/portal/73998424/Charlton_et_al_2023_Physiol._Meas._10.1088_1361_6579_acead2.pdf)

### Multi-wavelengths

- 2021-[A Review of Wearable Multi-Wavelength Photoplethysmography](https://pubmed.ncbi.nlm.nih.gov/34669577/)-35
- 2022-[Dual Wavelength Photoplethysmography Framework for Heart Rate Calculation](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9782066/)-2 | 【红外去噪】
- 2023-[Multiwavelength photoplethysmography signal analysis as a function of varied wrist contact pressure](https://ui.adsabs.harvard.edu/abs/2023SPIE12387E..07M/abstract)

### Multi-channels

- 2007-[Multichannel Reflective PPG Earpiece Sensor With Passive Motion Cancellation](https://ieeexplore.ieee.org/document/4404855)-143
- 2018-[Wearable Multichannel Photoplethysmography Framework for Heart Rate Monitoring During Intensive Exercise](https://ieeexplore.ieee.org/abstract/document/8279414)-55
- 2016-[Improving Pulse Rate Measurements during Random Motion Using a Wearable Multichannel Reflectance Photoplethysmograph](https://www.mdpi.com/1424-8220/16/3/342)-79
- 2019-[Organic Multi-Channel Optoelectronic Sensors for Wearable Health Monitoring](https://ieeexplore.ieee.org/document/8826261)-52
- 2020-[Motion Artifact Reduction in Wearable Photoplethysmography Based on Multi-Channel Sensors with Multiple Wavelengths](https://www.mdpi.com/1424-8220/20/5/1493)-80
- 2022-[A Critical Review of Deep Learning-Based Multi-Sensor Fusion Techniques](https://www.mdpi.com/1424-8220/22/23/9364)-4


### Peak detection

- 2013-[Systolic peak detection in acceleration photoplethysmograms measured from emergency responders in tropical conditions](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0076585)-187
- 2014-[An Efficient and Automatic Systolic Peak Detection Algorithm for Photoplethysmographic Signals](https://www.researchgate.net/publication/271156444_An_Efficient_and_Automatic_Systolic_Peak_Detection_Algorithm_for_Photoplethysmographic_Signals)
- 2019-[Analysing noisy driver physiology real-time using off-the-shelf sensors: Heart rate analysis software from the taking the fast lane project](https://openresearchsoftware.metajnl.com/articles/10.5334/jors.241)-79
- 2020-[A robust PPG onset and systolic peak detection algorithm based on Hilbert transform](https://ieeexplore.ieee.org/document/9106571)-8
- 2020-[Improved Peak Detection Algorithm for Photoplethysmographic Signals](https://ieeexplore.ieee.org/document/9299546)-2
- 2022-[Robust PPG Peak Detection Using Dilated Convolutional Neural Networks](https://www.mdpi.com/1424-8220/22/16/6054)-12 | [code](https://github.com/HealthSciTech/Robust_PPG_PD)

### Artifacts removal

- 2020-[Robust PPG motion artifact detection using a 1-D convolution neural network](https://www.sciencedirect.com/science/article/abs/pii/S0169260720314292)-44
- 2021-[An Accurate Non-accelerometer-based PPG Motion Artifact Removal Technique using CycleGAN](https://arxiv.org/abs/2106.11512)-24
- 2023-[**Tiny-PPG: A Lightweight Deep Neural Network for Real-Time Detection of Motion Artifacts in Photoplethysmogram Signals on Edge Devices**](https://arxiv.org/abs/2305.03308) | [code](https://github.com/SZTU-wearable/Tiny-PPG)
- 2023-[Opening the envelope: Efficient envelope-based PPG denoising algorithm](https://www.sciencedirect.com/science/article/pii/S1746809423011266)


### HR(Heart Rate)

- 2019-[DeepHeart: Accurate Heart Rate Estimation from PPG Signals Based on Deep Learning](https://ieeexplore.ieee.org/document/9077372)-12
- 2019-[Deep PPG: Large-Scale Heart Rate Estimation with Convolutional Neural Networks](https://pubmed.ncbi.nlm.nih.gov/31336894/)-229
- 2019-[HeartPy: A novel heart rate algorithm for the analysis of noisy signals](https://www.sciencedirect.com/science/article/abs/pii/S1369847818306740)-162 | [code](https://github.com/paulvangentcom/heartrate_analysis_python)
- 2019-[CorNET: Deep Learning Framework for PPG-Based Heart Rate Estimation and Biometric Identification in Ambulant Environment](https://ieeexplore.ieee.org/ielaam/4156126/8672973/8607019-aam.pdf)-228
- 2020-[Deep Learning for Heart Rate Estimation from Reflectance Photoplethysmography with Acceleration Power Spectrum and Acceleration Intensity](https://ieeexplore.ieee.org/document/9042276)-37
- 2020-[CNNs for Heart Rate Estimation and Human Activity Recognition in Wrist Worn Sensing Applications](https://staff.itee.uq.edu.au/jaga/proceedings/percomworkshops2020/papers/p3-brophy.pdf)-17
- 2021-[Real-Time System Prediction for Heart Rate Using Deep Learning and Stream Processing Platforms](https://www.hindawi.com/journals/complexity/2021/5535734/)-21
- 2021-[**Q-PPG: Energy-Efficient PPG-Based Heart Rate Monitoring on Wearable Devices**](https://pubmed.ncbi.nlm.nih.gov/34673496/)-27 | [code](https://github.com/eml-eda/q-ppg)
- 2021-[Heart rate tracking in photoplethysmography signals affected by motion artifacts: a review](https://d-nb.info/1228416095/34)-45
- 2021-[Multi-Headed Conv-LSTM Network for Heart Rate Estimation during Daily Living Activities](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8348622/)-13
- 2022-[Heart rate estimation in PPG signals using Convolutional-Recurrent Regressor](https://pubmed.ncbi.nlm.nih.gov/35381452/)-17
- 2022-[DeepPulse: An Uncertainty-aware Deep Neural Network for Heart Rate Estimations from Wrist-worn Photoplethysmography](https://www.techrxiv.org/articles/preprint/DeepPulse_An_Uncertainty-aware_Deep_Neural_Network_for_Heart_Rate_Estimations_from_Wrist-worn_Photoplethysmography/19368140)-3
- 2022-[ActPPG : Embedding Temporal Convolutional Networks for Energy-Efficient PPG-Based Heart Rate Monitoring](https://arxiv.org/pdf/2203.04396.pdf)-14
- 2022-[Robust and Energy-efficient PPG-based Heart-Rate Monitoring](https://arxiv.org/abs/2203.16339)-22
- 2023-[Are Activity Wrist-Worn Devices Accurate for Determining Heart Rate during Intense Exercise?](https://www.mdpi.com/2306-5354/10/2/254)-3
- 2023-[Precision Heart Rate Estimation Using a PPG Sensor Patch Equipped with New Algorithms of Pre-Quality Checking and Hankel Decomposition](https://www.mdpi.com/1424-8220/23/13/6180)
- 2023-[PPG-based Heart Rate Estimation with Efficient Sensor Sampling and Learning Models](https://arxiv.org/pdf/2303.13636.pdf)-1
- 2023-[Heart rate estimation from wrist-PPG signals in activity by deep learning methods](https://kth.diva-portal.org/smash/get/diva2:1801202/FULLTEXT01.pdf)-thesis 【有讨论多通道模型，相比于单通道提升12%】
- 2023-[**BeliefPPG: Uncertainty-aware Heart Rate Estimation from PPG signals via Belief Propagation**](https://arxiv.org/pdf/2306.07730.pdf) | [code](https://github.com/eth-siplab/BeliefPPG)
- 2023-[A Self-Supervised Algorithm for Denoising Photoplethysmography Signals for Heart Rate Estimation from Wearables](https://arxiv.org/abs/2307.05339v1)-code? | 【用 decoder 去恢复被破坏的波形】
- 2023-[Energy-efficient Wearable-to-Mobile Offload of ML Inference for PPG-based Heart-Rate Estimation](https://arxiv.org/pdf/2306.06129.pdf)-2
  
### SpO2(Blood oxygen saturation level/Pulse oximetry)

- 2013-[Pulse oximetry: Understanding its basic principles facilitates appreciation of its limitations](https://www.sciencedirect.com/science/article/pii/S095461111300053X)-696
- 2014-[Pulse oximetry: Fundamentals and technology update](https://www.researchgate.net/publication/264009809_Pulse_oximetry_Fundamentals_and_technology_update)-415
- 2015-[Pulse oximetry](https://ccforum.biomedcentral.com/articles/10.1186/s13054-015-0984-8)-902
- 2018-[Design of a new reflectance pulse oximeter by obtaining the optimal source-detector space](https://www.sciencedirect.com/science/article/abs/pii/S0030402618305242)-15
- 2019-[Machine Learning based SpO2 Computation Using Reflectance Pulse Oximetry](https://pubmed.ncbi.nlm.nih.gov/31945942/)-23
- 2020-[**Robust Modelling of Reflectance Pulse Oximetry for SpO2 Estimation**](https://arxiv.org/pdf/2004.06301.pdf)-7 | [code](https://github.com/prithusuresh/Reflectance-SPO2)
- 2021-[**Learning about reflective PPG for SpO2 determination using Machine Learning**](https://www.researchgate.net/publication/356917812_Learning_about_reflective_PPG_for_SpO2_determination_using_Machine_Learning)-1 | [ear]
- 2022-[Research on Multiple Spectral Ranges with Deep Learning for SpO2 Measurement](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8749643/)-3 | [finger]
- 2022-[**Skin Pigmentation Influence on Pulse Oximetry Accuracy: A Systematic Review and Bibliometric Analysis**](https://www.mdpi.com/1424-8220/22/9/3402)-36 | 【空气间隙以及皮肤颜色在校准过程中对最后结果的影响】
- 2022-[Research on Multiple Spectral Ranges with Deep Learning for SpO2 Measurement](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8749643/)-3
- 2023-[A Deep Learning Approach to Estimate SpO2 from PPG Signals](https://dl.acm.org/doi/10.1145/3569192.3569215)
- 2023-[SpO2 Estimation Using Deep Neural Networks: A Comparative Study](https://ieeexplore.ieee.org/document/10193267) | [finger+camera]
- 2023-[Everything About Pulse Oximetry—Part 1: History, Principles, Advantages, Limitations, Inaccuracies, Cost Analysis, the Level of Knowledge About Pulse Oximeter Among Clinicians, and Pulse Oximetry Versus Tissue Oximetry](https://journals.sagepub.com/doi/abs/10.1177/08850666231185752)
- 2023-[Reflection-Boosted Wearable Ring-Type Pulse Oximeters for SpO2 Measurement with High Sensitivity and Low Power Consumption](https://www.mdpi.com/2079-6374/13/7/711/pdf)
- 2023-[Machine Learning-Based Respiration Rate and Blood Oxygen Saturation Estimation Using Photoplethysmogram Signals](https://www.mdpi.com/2306-5354/10/2/167)-4
- 2023-[**Simulating the Effects of Melanin and Air Gap Depth on the Accuracy of Reflectance Pulse Oximeters**](https://www.scitepress.org/Papers/2023/117493/117493.pdf)-4
- 2023-[A review of the effect of skin pigmentation on pulse oximeter accuracy](https://iopscience.iop.org/article/10.1088/1361-6579/acd51a/pdf)-5

##  RR(Respiratory rate)

### BP(Blood Pressure)

## Books

- 2021-[Photoplethysmography: Technology, Signal Analysis and Applications, 1st Edition](https://www.amazon.com/Photoplethysmography-Technology-Signal-Analysis-Applications/dp/0128233745)

## Indices



## Tutorial

## Datasets



## Contributing

We welcome your contributions! Please follow these steps to contribute:

1. Fork the repo.
2. Create a new branch (e.g., `feature/new-ppg-resource`).
3. Commit your changes to the new branch.
4. Create a Pull Request, and provide a brief description of the changes/additions.

Please make sure that the resources you add are relevant to the field of Heart Rate Variability. Before contributing, take a look at the existing resources to avoid duplicates.

## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
