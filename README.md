# Starbucks-Customer-Segmentation-Project

### Introduction:
Marketing to potential customers is an important part of business for all organizations and using available data to feed into your marketing plans is a very important part of the whole process.

The task in this project was to use the available simulated data of Starbucks customers to understand which demographics responds to different offer.

### Reason for this project:
I have knowledge in marketing and thought that this will be a very practical way to learn how to understand customer patterns and then propose ways of targeting them using data.

### Libraries used:
- datetime
- pandas
- numpy
- math
- seaborn
- json
- matplotlib

#### Data Sets

The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

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

**transcript.json** file location: https://bit.ly/2EEAzlW
* event (str) - record description (ie transaction, offer received, offer viewed, etc.)
* person (str) - customer id
* time (int) - time in hours since start of test. The data begins at time t=0
* value - (dict of strings) - either an offer id or transaction amount depending on the record

### Summary of results
In summary, segementing customers can help in understand a particular target audience and creating personas along empathy maps to successful create a profile for the kind of customers Starbuck will like to attract. For this project the idea was geard towards looking at customers that have buying power and are willing to pay for cup of coffee or other products to ensure sustained sales. I went from understanding each component to comparing two to three components and found out that with increased age, there were more transactions. Also with increase age saw an increase in income. This can be due to advancement in career (i.e the more years spent in a field, the more you are paid). Between low income to middle income, males earned more and made more transactions but from middle to high icome and high income demographics, there were more females and they contributed higher to trasactions. These customers responded better to discount campaigns than BOGO campaigns.Segementing by income was the best way to look at other demographics putting sales in mind. The Starbucks brand has to stay alive in the minds of both the young and the elderly and there's no better way than to target their specific needs than to attempt sending various campaigns.

### Acknoledgements
* Stack Overflow
* Friends from Port Harcourt School of AI.
