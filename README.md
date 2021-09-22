# Udacity's Starbucks Capstone Challenge


![Udacity's logo](https://upload.wikimedia.org/wikipedia/commons/thumb/3/3b/Udacity_logo.png/800px-Udacity_logo.png)

For this capstone, we have to study the given data from Starbucks to gain further insights and to create models that could be deployed. The study will be structured as follow :
* Project Definition : Project overview, problem statement and metrics
* Data : Preliminary evaluation and cleaning, wrangling and analysis
* Summary of analysis
* Feature engineering
* Model building, evaluation and hyperparameter tuning
* Discussion
* Conclusion

The project is about analyzing Starbucks data of multiple users, to understand the effectiveness of three promotional offers , sent randomly to random users. It's an experiment made over a period of 30 days . During that period, Starbucks sent randomly without prior knowledge, one of three types of offers also randomly chosen. All of these offers come with different configurations as with different periods of validity and have been shared with costumers in different ways.

## Data Sets

The data is contained in three files:

portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
profile.json - demographic data for each customer
transcript.json - records for transactions, offers received, offers viewed, and offers completed
Here is the schema and explanation of each variable in the files:

**portfolio.json**

* id (string) - offer id
* offer_type (string) - type of offer ie BOGO, discount, informational
* difficulty (int) - minimum required spend to complete an offer
* reward (int) - reward given for completing an offer
* duration (int) - time for offer to be open, in days
* channels (list of strings)

**profile.json**

* age (int) - age of the customer
* became_member_on (int) - date when customer created an app account
* gender (str) - gender of the customer (note some entries contain 'O' for other rather than M or F)
* id (str) - customer id
* income (float) - customer's income

**transcript.json**

* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record


## Prerequisites and Instructions

### Dependencies

To run the project app and pipeline scripts, the user needs to intall the folowing items : 

* **Python 3.6x**
* **Libraries: NumPy, SciPy, Pandas, Sciki-Learn, seaborn, matplotlib, stats, statsmodels**

### How to:

* **Downloading** : To download and use the project , clone the repo by using this command : 

  * `git clone https://github.com/ElMedBen/udacity_captstone_datascience.git`

* **Running** : To use the project, launch the notebook and run the cells

## Folder structure :
```
├─ Starbucks_Capstone_notebook_benammi.ipynb
├─ data
│  ├─ portfolio.json : containing offer ids and meta data about each offer (duration, type, etc.)
│  ├─ profile.json : demographic data for each customer
│  └─ transcript.json : records for transactions, offers received, offers viewed, and offers completed
└─ README.md
```
## Author
[El Mehdi Benammi](https://github.com/ElMedBen)

## License 
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

![Starbucks's logo](https://logoeps.com/wp-content/uploads/2011/04/starbucks-logo-vector.png)
