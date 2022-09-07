# SEB_big_data_challenge_2020

Data regarding "good" and "bad" loans (data will not be shared).
During the challange data was fetched through Kafka.

Challange aftermath (12th place):
https://www.linkedin.com/posts/gsakalas_seb-confluent-bigdata-activity-6735201804058943488-76tr

With limited time not much was done:
* Fixed missing values (some were dropped, some were imputed using KNNs, some were added through quick interpretation of data)
* Fixed only some (most ridiculious) outliers
* Tested only Random Forests classification method (with various parameters)

Some topics for further (and ongoing) investigations:
* Investigate outliers and missing values
* Scale the data
* Investigate various data slices
* Try other classification methods
