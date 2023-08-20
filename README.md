# My-Activity-Recognition-and-Anomaly-Detection-Research-Repo

# Anomaly Detection

- Activity Recognition
- Anomaly Detection

Below is the list of IMU datasets for the Anomaly Detection task along with the corresponding links to models, code, and the year they were published.

## Datasets

1. **ELKI Outlier Datasets** - [https://www.dbs.ifi.lmu.de/research/outlier-evaluation/](#) - Year 2016

   Brief Description: This repository contains outlier detection datasets and the results of basic kNN-based outlier detection methods on these datasets and aggregated results over the methods and datasets.

2. **Outlier Detection Datasets (ODDS)** - [https://odds.cs.stonybrook.edu/#table1](#) - Year 2016

   Brief Description: ODDS openly provides access to a large collection of outlier detection datasets with ground truth (if available). The focus is to provide datasets from different domains and present them under a single umbrella for the research community.

3. **Unsupervised Anomaly Detection Dataverse** - [https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/OPQMVF](#) - Year 2015

   Brief Description: These datasets can be used for benchmarking unsupervised anomaly detection algorithms (for example, "Local Outlier Factor" LOF). The datasets have been obtained from multiple sources and are mainly based on datasets originally used for supervised machine learning. By publishing these modifications, a comparison of different algorithms is now possible for unsupervised anomaly detection.

4. **Anomaly Detection Meta-Analysis Benchmarks** - [https://ir.library.oregonstate.edu/concern/datasets/47429f155](#) - Year 2016

   Brief Description: The dataset provides a comprehensive collection of anomaly detection benchmarks. It includes various benchmarks with different characteristics relevant to real-world applications. The dataset enables the evaluation of anomaly detection algorithms and offers insights into experimental design, performance metrics, algorithm strengths/weaknesses, and potential challenges in measuring success in the field.

5. **The MVTEC Anomaly Detection Dataset (MVTEC AD)** - [https://www.mvtec.com/company/research/datasets/mvtec-ad](#) - Year 2020

   Brief Description: MVTec AD is a dataset for benchmarking anomaly detection methods with a focus on industrial inspection. It contains over 5000 high-resolution images divided into fifteen different object and texture categories. Each category comprises a set of defect-free training images and a test set of images with various kinds of defects as well as images without defects.

6. **ShanghaiTech Campus dataset (Anomaly Detection)** - [https://svip-lab.github.io/dataset/campus_dataset.html](#) - Year 2016

   Brief Description: It is desirable that the anomaly detection model trained can be directly applied in multiple scenes with multiple view angles. However, almost all existing datasets only contain videos captured with one fixed-angle camera, and it lacks the diversity of scenes and view angles. To increase scene diversity, we build a new anomaly detection dataset. Further, we introduce the anomalies caused by sudden motion in this dataset, such as chasing and brawling in our dataset, which are not included in existing datasets. These characteristics make our dataset more suitable for real scenarios.

7. **Numenta Anomaly Benchmark (NAB)** - [https://www.kaggle.com/datasets/boltzmannbrain/nab](#) - Year 2015

   Brief Description: The Numenta Anomaly Benchmark (NAB) is a novel benchmark for evaluating algorithms for anomaly detection in streaming, online applications. It is comprised of over 50 labeled real-world and artificial time series data files plus a novel scoring mechanism designed for real-time applications.

## Models and Tools

1. **EGADS Java Library** - [https://github.com/yahoo/egads](#) - Year 2021

   Brief Description: EGADS (Extensible Generic Anomaly Detection System) is an open-source Java package to automatically detect anomalies in large-scale time-series data. EGADS is meant to be a library that contains several anomaly detection techniques applicable to many use cases in a single package with the only dependency being Java.

2. **Awesome-Deep-Graph-Anomaly-Detection** - [https://github.com/XiaoxiaoMa-MQ/Awesome-Deep-Graph-Anomaly-Detection#anomalous-edge-detection](#) - Year 2022

   Brief Description: A collection of models, papers, and datasets on deep learning for graph anomaly detection.

3. **MLF-SC: Incorporating Multi-Layer Features to Sparse Coding for Unsupervised Anomaly Detection** - [https://github.com/LeapMind/MLF-SC](#) - Year 2020

   Brief Description: MLF-SC (Multi-Layer Feature Sparse Coding) is an anomaly detection method that incorporates multi-scale features to sparse coding. This is a PyTorch implementation for MVTec datasets (Carpet, Grid, Leather, Tile, Wood, ...).

4. **Python Outlier Detection (PyOD)** - [https://github.com/yzhao062/pyod](#) - [https://github.com/yzhao062/pyod#implemented-algorithms](#) - Year 2023

   Brief Description: PyOD is a comprehensive and scalable Python toolkit for detecting outlying objects in multivariate data. It contains more than 20 detection algorithms, including emerging deep learning models and outliers ensembles.

5. **(Py)TOD: GPU-accelerated Outlier Detection via Tensor Operations** - [[Link](https://github.com/yzhao062/pytod)](#) - [[Link](https://github.com/yzhao062/pytod#implemented-algorithms)](#) - Year 2022

   Brief Description: A general GPU-accelerated framework for outlier detection.

## Surveys and Overview

1. **Anomaly detection: A survey** - [[Link](https://conservancy.umn.edu/bitstream/handle/11299/215731/07-017.pdf?sequence=1)](#) - Year 2009

   Brief Description: The paper "Anomaly Detection: A Survey" provides a comprehensive overview of anomaly detection techniques, categorizing them based on their approaches. It discusses the importance of anomaly detection across domains such as intrusion detection and fraud detection, highlighting challenges in defining normal behavior. The paper explores various techniques including classification, nearest-neighbor, and statistical methods.
