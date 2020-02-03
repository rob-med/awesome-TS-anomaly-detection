# awesome-TS-anomaly-detection
> List of tools & datasets for **anomaly detection on _time-series_ data**.

All lists are in alphabetical order. 
A repository is considered "not maintained" if the latest commit is > 1 year old, or explicitly mentioned by the authors.

## Anomaly Detection Software


| Name          | Language       | Pitch     | License | Maintained
| ------------- |:-------------: | :-------------: |  :-------------:  |  :-------------:     
| Expedia.com's [Adaptive Alerting](https://github.com/ExpediaDotCom/adaptive-alerting) | Java | Streaming anomaly detection with automated model selection and fitting. | Apache-2.0 | :heavy_check_mark:
| Arundo's [ADTK](https://github.com/arundo/adtk) | Python | Anomaly Detection Toolkit (ADTK) is a Python package for unsupervised / rule-based time series anomaly detection. | MPL 2.0 | :heavy_check_mark:
| Twitter's [AnomalyDetection](https://github.com/twitter/AnomalyDetection)| R      |AnomalyDetection is an open-source R package to detect anomalies which is robust, from a statistical standpoint, in the presence of seasonality and an underlying trend.   | GPL | ❌
| Lytics' [Anomalyzer](https://github.com/lytics/anomalyzer)                | Go     | Anomalyzer implements a suite of statistical tests that yield the probability that a given set of numeric input, typically a time series, contains anomalous behavior.    | Apache-2.0 | ❌
| [banpei](https://github.com/tsurubee/banpei)| Python | Outlier detection (Hotelling's theory) and Change point detection (Singular spectrum transformation) for time-series. | MIT | :heavy_check_mark:
| Ele.me's [banshee](https://github.com/facesea/banshee)                     | Go     |Anomalies detection system for periodic metrics. | MIT | ❌
| [CAD](https://github.com/smirmik/CAD) | Python | Contextual Anomaly Detection for real-time AD on streagming data (winner algorithm of the 2016 NAB competition). | AGPL | ❌
| Mentat's [datastream.io](https://github.com/MentatInnovations/datastream.io)| Python |An open-source framework for real-time anomaly detection using Python, Elasticsearch and Kibana. | Apache-2.0 |  ❌
| [DeepADoTS](https://github.com/KDD-OpenSource/DeepADoTS) | Python | Implementation and evaluation of 7 deep learning-based techniques for Anomaly Detection on Time-Series data. | MIT | :heavy_check_mark:
| [Donut](https://github.com/korepwx/donut)| Python | Donut is an unsupervised anomaly detection algorithm for seasonal KPIs, based on Variational Autoencoders. | - | :heavy_check_mark:
| Yahoo's [EGADS](https://github.com/yahoo/egads)                          | Java   |GADS is a library that contains a number of anomaly detection techniques applicable to many use-cases in a single package with the only dependency being Java.    | GPL | :heavy_check_mark:
| Linkedin's [luminol](https://github.com/linkedin/luminol)                | Python |Luminol is a light weight python library for time series data analysis. The two major functionalities it supports are anomaly detection and correlation. It can be used to investigate possible causes of anomaly. | Apache-2.0  | ❌  
| [MIDAS](https://github.com/bhatiasiddharth/MIDAS) | C++ | MIDAS, short for Microcluster-Based Detector of Anomalies in Edge Streams, detects microcluster anomalies from an edge stream in constant time and memory. | Apache-2.0 | :heavy_check_mark:
| Numenta's [Nupic](https://github.com/numenta/nupic)                      | C++    |Numenta Platform for Intelligent Computing is an implementation of Hierarchical Temporal Memory (HTM).   | AGPL |  :heavy_check_mark:
| [oddstream](https://github.com/pridiltal/oddstream)| R | oddstream (Outlier Detection in Data Streams) provides real time support for early detection of anomalous series within a large collection of streaming time series data. | GPL-3 |  :heavy_check_mark:
| [PyOdds](https://github.com/datamllab/pyodds)| Python | PyODDS is an end-to end Python system for outlier detection with database support. PyODDS provides outlier detection algorithms, which support both static and time-series data.  | MIT |  :heavy_check_mark:
| [rrcf](https://github.com/kLabUM/rrcf) | Python | Implementation of the Robust Random Cut Forest algorithm for anomaly detection on streams. | MIT |  :heavy_check_mark:
| Etsy's [Skyline](https://github.com/etsy/skyline)                        | Python |Skyline is a real-time anomaly detection system, built to enable passive monitoring of hundreds of thousands of metrics. | MIT  | ❌ 
| Netflix's [Surus](https://github.com/netflix/surus)                      | Java   |Robust Anomaly Detection (RAD) - An implementation of the Robust PCA.   | Apache-2.0 | ❌ 
| NASA's [Telemanom](https://github.com/khundman/telemanom)| Python | A framework for using LSTMs to detect anomalies in multivariate time series data. Includes spacecraft anomaly data and experiments from the Mars Science Laboratory and SMAP missions.  | [custom](https://github.com/khundman/telemanom/blob/master/LICENSE.txt) |  :heavy_check_mark:

## Related Software

This section includes some time-series software for anomaly detection-related tasks, such as forecasting and labeling.

### Forecasting

| Name          | Language       | Pitch     | License  | Maintained
| ------------- |:-------------: | :-------------: |  :-------------: |  :-------------:   
| Amazon's [GluonTS](https://github.com/awslabs/gluon-ts) | Python | GluonTS is a Python toolkit for probabilistic time series modeling, built around MXNet. GluonTS provides utilities for loading and iterating over time series datasets, state of the art models ready to be trained, and building blocks to define your own models. | Apache-2.0 |  :heavy_check_mark:
| [pmdarima](https://github.com/tgsmith61591/pyramid) | Python | Porting of R's _auto.arima_ with a scikit-learn-friendly interface. | MIT | :heavy_check_mark:
| Facebook's [Prophet](https://github.com/facebook/prophet) | Python/R | Prophet is a procedure for forecasting time series data. It is based on an additive model where non-linear trends are fit with yearly and weekly seasonality, plus holidays. | BSD |  :heavy_check_mark:
| [PyFlux](https://github.com/RJT1990/pyflux) | Python | The library has a good array of modern time series models, as well as a flexible array of inference options (frequentist and Bayesian) that can be applied to these models. | BSD 3-Clause | ❌
| [SaxPy](https://github.com/seninp/saxpy) | Python | General implementation of SAX, as well as HOTSAX for anomaly detection. | GPLv2.0 | :heavy_check_mark:
| [seglearn](https://github.com/dmbee/seglearn) | Python | Seglearn is a python package for machine learning time series or sequences. It provides an integrated pipeline for segmentation, feature extraction, feature processing, and final estimator. | BSD 3-Clause | :heavy_check_mark:
| [Tigramite](https://github.com/jakobrunge/tigramite) | Python | Tigramite is a causal time series analysis python package. It allows to efficiently reconstruct causal graphs from high-dimensional time series datasets and model the obtained causal dependencies for causal mediation and prediction analyses.| GPLv3.0 | :heavy_check_mark:
| [tslearn](https://github.com/rtavenar/tslearn) | Python | tslearn is a Python package that provides machine learning tools for the analysis of time series. This package builds on scikit-learn, numpy and scipy libraries. | BSD 2-Clause | :heavy_check_mark:

### Labeling

| Name          | Language       | Pitch     | License | Maintained
| ------------- |:-------------: | :-------------: |  :-------------:  |  :-------------:
| Baidu's [Curve](https://github.com/baidu/Curve) | Python | Curve is an open-source tool to help label anomalies on time-series data. | Apache-2.0 | :heavy_check_mark:
| Microsoft's [Taganomaly](https://github.com/Microsoft/TagAnomaly) | R (dockerized web app) | Simple tool for tagging time series data. Works for univariate and multivariate data, provides a reference anomaly prediction using Twitter's AnomalyDetection package. | MIT | :heavy_check_mark:


## Benchmark Datasets

- Numenta's [NAB](https://github.com/numenta/NAB)
> NAB is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications. It is comprised of over 50 labeled real-world and artificial timeseries data files plus a novel scoring mechanism designed for real-time applications.
- Yahoo's [Webscope S5](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70)
> The dataset consists of real and synthetic time-series with tagged anomaly points. The dataset tests the detection accuracy of various anomaly-types including outliers and change-points. 
