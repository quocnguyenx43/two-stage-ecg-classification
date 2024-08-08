- China 12-Lead ECG Challenge Database (China_12leads_Challenge): 
    + 12 leads (10s - 60s)
    + 500 Hz
    + multi-labels (đơn nhãn normal, đã nhãn bệnh)
    + information: age, sex,...
    + link paper: A large-scale multi-label 12-lead electrocardiogram database with standardized diagnostic statements
    + link dataset: https://springernature.figshare.com/collections/A_large-scale_multi-label_12-lead_electrocardiogram_database_with_standardized_diagnostic_statements/5779802/1
- China Physiological Signal Challenge 2018 (CPSC):
    + 12 leads (6s - 60s)
    + 500 Hz
    + multi-labels (đơn nhãn normal, đã nhãn bệnh)
    + information: age, sex,...
    + link paper: http://2018.icbeb.org/Challenge.html
    + link dataset: http://2018.icbeb.org/Challenge.html
- PTB XL (merge được nhưng mà nó có nhiều bệnh ko có trong AHA):
    + 12 leads (10s)
    + original: 400Hz; 500Hz & 100Hz
    + multi-labels (SCP-ECG statements): mỗi class sẽ có 1 likelihood chồng chéo, có thể có sample vừa 100% không bệnh và 100% bệnh (rất khó hiểu)
    + information: demographics, diagnosis statements, diagnosis likelihoods
    + link paper: PTB-XL, a large publicly available electrocardiography dataset
    + link dataset: https://physionet.org/content/ptb-xl/1.0.3/
    + code merge tham khảo:
        + https://github.com/burkelawlor/ecg_classification/blob/main/data_cleaning/data_cleaning.ipynb
- Chapman: 
    + 12 leads (10s)
    + 500Hz
    + information: 
    + link paper:
        + A 12-lead electrocardiogram database for arrhythmia research covering more than 10,000 patients
        + Optimal Multi-Stage Arrhythmia Classification Approach
    + link dataset:
        + https://physionet.org/content/ecg-arrhythmia/1.0.0/
        + https://figshare.com/collections/ChapmanECG/4560497/2
- PTB:
    + 15 leads - 14 for ECGs, 1 for respiration, 1 for line voltage (xxs)
    + 1000 Hz
    + labels (diagnose đơn nhãn): healthy control - 19%
    + information: age, sex, date, smoker or not,...
    + link dataset: https://physionet.org/content/ptbdb/1.0.0/
- St Petersburg INCART 12-lead Arrhythmia Database:
    + 12 leads (30m)
    + 257Hz
    + multi-labels: normal 14/32 người
    + information: sex, age,...
    + link paper: https://physionet.org/content/incartdb/1.0.0/
    + link dataset: https://physionet.org/content/incartdb/1.0.0/
- A large scale 12-lead electrocardiogram database for arrhythmia study (Shaoxing People’s Hospital dataset) - 
- Challenge: https://physionet.org/content/challenge-2020/1.0.2/training/georgia/#files-panel
- Challenge 2021: https://www.physionet.org/content/challenge-2021/1.0.2/papers/#scoring