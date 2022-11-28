## Data Modelling for NoSQL data

Data pipeline to load data from a set of csv of files to casandra is created. The nature of queries to be executed on casandra a known apriori. 

### Dataset
The raw data is in the form of csv files. The data comes from a music streaming service. There are broadly two kinds of data:
- User Activity Data
- Songs Data

The broad question(s) that need to be answered from the casandra database pertains to the songs currently being played to by subscriber and general users.

The raw data is in a directory, partitioned by date. Following the directory structure:

```
event_data/2018-11-08-events.csv
event_data/2018-11-09-events.csv
```

### How to run the project?
Refer to the file `packages.txt` for the python packages needed to run this project. After you have created the environment based on the packages, run the notebook `01.ipynb`
