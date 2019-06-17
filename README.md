# flight-look-to-book
This project contains two parts:
1. **Data analysis** for flight look-to-book statistics, as preprocessing for the machine learning forecast models
2. **Forecast models** (attempt)

Confluence page: (coming)


### Description:
It contains links to the raw datasets, including 'bookings' and 'searches' of the flights worldwide in 2013.

```flight-look-to-book-preprocessing_v0.ipynb``` is the initial version of work, reflecting most of the progress history.

```flight-look-to-book-preprocessing_v1.ipynb``` serves as a cleaner version of solutions to all the 4 questions.

```bonus-flight-ltb-forecast-naive-bayesian_v0.ipynb``` shows the skeleton of forecast, based on the principle of Naive Bayesian. However, it is incomplete yet due to computing power and timing issue.

```bonus-flight-ltb-forecast-xgboost_v0.ipynb``` provides an insight to the Extreme Gradient Boosting Classifier. However, it is incomplete yet due to computing power and timing issue.


### Prerequisites:
python --version
Python 3.6.8 :: Anaconda, Inc.

pandas (a python library) version:
0.24.2

uname -a
Linux 4.15.0-46-generic #49-Ubuntu SMP x86_64 x86_64 x86_64 GNU/Linux


### Usage:
```flight-look-to-book-preprocessing_v1.ipynb``` is runnable (yet recommend to SKIP the "Explore" section in solution 4 since it's dependent on hardware performance).
