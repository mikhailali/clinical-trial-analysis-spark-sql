# clinical-trial-analysis-spark-sql
In this notebook, I analyse a dataset where each row corresponds to a clinical trial. There is a variety of information about the clinical trial given, such as the trial name, the conditions being monitored, and the start and completion times of the trial. The dataset contains around 500,000 rows, so Spark SQL is a good module for data processing, as this can be considered Big Data.

There are four questions relating to the dataset which we want to find the answers to, and I provide SQL queries in order to find this information. 

Our goals are to:
- Determine the frequency of each study type.
- Identify the top 10 most common conditions.
- Compute the average trial duration in months.
- Visualise trends in diabetes‑related trials over time.

By revealing these insights, I aim to help researchers and decision‑makers better understand trial designs, durations, and focus areas.
