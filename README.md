## 📊 Dataset: Ashen Dataset

The Ashen Dataset is a focused surveillance benchmark consisting of **1,600 untrimmed real-world videos**. It was curated to specifically target **hostile-intent anomaly categories** relevant to public safety and institutional security.

### Class Distribution

The dataset features a perfectly balanced anomaly distribution with **100 videos per anomaly category** and **800 normal videos**, ensuring model evaluations are not biased by class prevalence.

| Class | Type | Videos | Total Frames |
| --- | --- | --- | --- |
| **Normal** | Normal | 800 | 9,474,387 

 |
| **Arson** | Anomaly | 100 | 355,086 

 |
| **Assault** | Anomaly | 100 | 140,369 

 |
| **Burglary** | Anomaly | 100 | 471,206 

 |
| **Explosion** | Anomaly | 100 | 325,903 

 |
| **Fighting** | Anomaly | 100 | 419,265 

 |
| **Robbery** | Anomaly | 100 | 311,973 

 |
| **Shooting** | Anomaly | 100 | 190,737 

 |
| **Vandalism** | Anomaly | 100 | 272,598 

 |
| **Total** |  | **1,600** | <br>**11,961,524** 

 |

### Dataset Split (70/15/15)

To prevent information leakage and ensure reproducibility, the dataset is partitioned using strict video-level stratified random sampling.

| Split | Normal Videos | Anomaly Videos (Total) | Total Videos |
| --- | --- | --- | --- |
| **Training** | 557 

 | 560 (70 per class) 

 | <br>**1,117** 

 |
| **Validation** | 119 

 | 120 (15 per class) 

 | <br>**239** 

 |
| **Test** | 120 

 | 120 (15 per class) 

 | <br>**240** 

 |

* 
**Training Set**: Used for model optimization.


* 
**Validation Set**: Used exclusively for hyperparameter tuning and model selection.


* 
**Test Set**: Used only for final performance reporting to reflect genuine generalization.
