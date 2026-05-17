# Log-Based-Anomaly-Detection-In-Open-Source-Cloud-Infrastructure-Automation-Using-Machine-Learning


Cloud is being used pretty much everywhere nowadays and cloud service providers have to keep it up and running for thousands of customers who run their services using cloud. The log entries from these services contains very important information with regards to the behaviour about failures, anomaly detection and so on. Existing approach in the provider level Site Reliability Engineering(SRE) is to define a threshold value by defining alerting rules to detect the failures or abnormality in the infrastructure. Defining such rules is a tedious task and it does not notify upcoming problem to the SRE until and unless the threshold is reached.

Various Machine Learning and Deep Learning algorithm are used for the anomaly detection. Several algorithms of supervised and unsupervised learning are used to detect anomalies by employing the log parsing and dimensionality reduction techniques.

## Implementation 

### Data Collection 

Graylog is used to export the csv file containing Openstack logs

### Data Cleaning and Preprocessing

Tests were conducted using Drain, IPLoM log parsers which took significantly very high time to parse the log messages. Custom stoopword list were used and regex were written based on the domain knowledge.

### Feature Engineering

1. Count Vectorizer
2. Tf-idf Vectorizer
3. One hot encoding
4. Auto Encoders
5. Word 2 Vec
6. Dimensionality reduction using PCA

### Models

1. Local Outlier Factor
2. Isolation Forest
3. Copula Based Outlier Detection (COPOD)
4. Empirical Cumulative Based Outlier Detection (ECOD)
5. LSTM and Bi-LSTM
6. Ensemble Model



