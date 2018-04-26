# awesome-TS-anomaly-detection
> List of tools & datasets for **anomaly detection on _time-series_ data**.

## Anomaly Detection Software


| Name          | Language       | Pitch     
| ------------- |:-------------: | :-------------:     
| Numenta's [Nupic](https://github.com/numenta/nupic)                      | C++    |Numenta Platform for Intelligent Computing is an implementation of Hierarchical Temporal Memory (HTM).   
| Etsy's [Skyline](https://github.com/etsy/skyline)                        | Python |Skyline is a real-time anomaly detection system, built to enable passive monitoring of hundreds of thousands of metrics.   
| Twitter's [AnomalyDetection](https://github.com/twitter/AnomalyDetection)| R      |AnomalyDetection is an open-source R package to detect anomalies which is robust, from a statistical standpoint, in the presence of seasonality and an underlying trend.   
| Netflix's [Surus](https://github.com/netflix/surus)                      | Java   |Robust Anomaly Detection (RAD) - An implementation of the Robust PCA.   
| Lytics [Anomalyzer](https://github.com/lytics/anomalyzer)                | Go     | Anomalyzer implements a suite of statistical tests that yield the probability that a given set of numeric input, typically a time series, contains anomalous behavior.    
| Yahoo's [EGADS](https://github.com/yahoo/egads)                          | Java   |GADS is a library that contains a number of anomaly detection techniques applicable to many use-cases in a single package with the only dependency being Java.    
| Linkedin's [luminol](https://github.com/linkedin/luminol)                | Python |Luminol is a light weight python library for time series data analysis. The two major functionalities it supports are anomaly detection and correlation. It can be used to investigate possible causes of anomaly.      
| Ele.me's [banshee](https://github.com/eleme/banshee)                     | Go     |Anomalies detection system for periodic metrics.
| Mentat's [datastream.io](https://github.com/MentatInnovations/datastream.io)| Python |An open-source framework for real-time anomaly detection using Python, Elasticsearch and Kibana.
| [Donut](https://github.com/korepwx/donut)| Python | Donut is an unsupervised anomaly detection algorithm for seasonal KPIs, based on Variational Autoencoders.

## Related Software

This section includes some time-series software for anomaly detection-related tasks, such as forecasting.


| Name          | Language       | Pitch     
| ------------- |:-------------: | :-------------:   
| Facebook's [Prophet](https://github.com/facebook/prophet) | Python/R | Prophet is a procedure for forecasting time series data. It is based on an additive model where non-linear trends are fit with yearly and weekly seasonality, plus holidays.
| [PyFlux](https://github.com/RJT1990/pyflux) | Python | The library has a good array of modern time series models, as well as a flexible array of inference options (frequentist and Bayesian) that can be applied to these models.
| [Pyramid](https://github.com/tgsmith61591/pyramid) | Python | Porting of R's _auto.arima_ with a scikit-learn-friendly interface.
| [SaxPy](https://github.com/seninp/saxpy) | Python | General implementation of SAX, as well as HOTSAX for anomaly detection.


## Benchmark Datasets

- Numenta's [NAB](https://github.com/numenta/NAB)
> NAB is a novel benchmark for evaluating algorithms for anomaly detection in streaming, real-time applications. It is comprised of over 50 labeled real-world and artificial timeseries data files plus a novel scoring mechanism designed for real-time applications.
- Yahoo's [Webscope S5](https://webscope.sandbox.yahoo.com/catalog.php?datatype=s&did=70)
> The dataset consists of real and synthetic time-series with tagged anomaly points. The dataset tests the detection accuracy of various anomaly-types including outliers and change-points. 
