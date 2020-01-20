# PharmaLobby

The goal of my Insight Data Engineering project is to design a real-time streaming pipeline and Web UI to check payments to Physicians by the Pharmaceutical companies and alert whenever a physician receives cumulative amount greater than a threshold from a Pharmaceutical company and also display top Pharmaceutical companies paying more amount and the most common side effects of the drugs manufactured by these Pharmaceutical companies.


Background


Open Payments is a federal program that collects and makes information public about financial relationships between the health care industry, physicians, and teaching hospitals.https://www.cms.gov/OpenPayments/.It has been updated from 2013 to 2018 and has about 36Gb of data in csv format.

DailyMed provides trustworthy information about marketed drugs in the United States. DailyMed is the official provider of FDA label information.https://dailymed.nlm.nih.gov/dailymed/.The dataset is about 25Gb in xml format and has been updated for last 7 months.
The dataset has all information like drug trials, side effects and post release experiences recorded for many of the drug labels produced by the pharmaceutical companies.

Is public aware of this? How are the drugs coming into market? Can public rely on the drugs prescribed?

I would like to test and see this scenario i.e. If the transactions in hospitals are monitored in real time and whenever there is transaction between any Physicians and Pharmaceutical companies, can we track and alert incase the payments are above a normal threshold? And can we just see what are top Pharmaceutical companies making payments and also the side effects of their drugs? Yes I want to try this and hence will build a data pipeline for the same.



