# Fetal_Health
# Fetal Health Classification

This repository contains a dataset and code related to the classification of fetal health.

## Dataset

The dataset used in this project is `fetal_health.csv`. It contains various features extracted from cardiotocogram exams, along with a fetal health classification.

**Features:**

* **baseline value:** Baseline fetal heart rate (FHR)
* **accelerations:** Number of accelerations per second
* **fetal_movement:** Number of fetal movements per second
* **uterine_contractions:** Number of uterine contractions per second
* **light_decelerations:** Number of light decelerations per second
* **severe_decelerations:** Number of severe decelerations per second
* **prolongued_decelerations:** Number of prolonged decelerations per second
* **abnormal_short_term_variability:** Percentage of time with abnormal short term variability
* **mean_value_of_short_term_variability:** Mean value of short term variability
* **percentage_of_time_with_abnormal_long_term_variability:** Percentage of time with abnormal long term variability
* **mean_value_of_long_term_variability:** Mean value of long term variability
* **histogram_width:** Width of FHR histogram
* **histogram_min:** Minimum (low frequency) of FHR histogram
* **histogram_max:** Maximum (high frequency) of FHR histogram
* **histogram_number_of_peaks:** Number of peaks in FHR histogram
* **histogram_number_of_zeroes:** Number of zeroes in FHR histogram
* **histogram_mode:** Mode of FHR histogram
* **histogram_mean:** Mean of FHR histogram
* **histogram_median:** Median of FHR histogram
* **histogram_variance:** Variance of FHR histogram
* **histogram_tendency:** Tendency of FHR histogram

**Target Variable:**

* **fetal_health:** Classified as 1 (Normal), 2 (Suspect), or 3 (Pathological)

## Code

The code provided demonstrates how to:

* Load and preprocess the dataset.
* Calculate class weights to address class imbalance.
* Train a deep learning model for fetal health classification.


## License

This project is licensed under the MIT License.
