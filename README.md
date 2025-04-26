# Anomaly-Detection-on-Security-Logs

1.Dataset: Loaded from /content/drive/My Drive/CICIDS2017/MachineLearningCVE/MachineLearningCVE/Monday-WorkingHours.pcap_ISCX.csv.

2.Model: Isolation Forest with 100 estimators and 5% contamination, trained on 78 numeric features.

3.Output: Predictions (anomaly_score: 1 = normal, -1 = anomaly; is_anomaly: 0 = normal, 1 = anomaly) alongside the original " Label".
