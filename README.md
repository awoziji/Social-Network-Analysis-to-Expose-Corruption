# Social Network Analysis to Expose Corruption

The Administrative Enforcement Unit (AEU) at the Department of Buildings is responsible for processing Certificates of Correction where an industry member is claiming to correct a building violation. Many of these certificates are processed in-person.

The objective of this analysis is to uncover potential corrupt social interactions between an industry member and the staff at the DOB. It is based on the assumption that long-term, repeated interactions between members of the construction industry and a single staff member are a measure of corruption.

The Python program develops a number of social interaction measures between an industry member and a staff member and uses Z-score outlier analysis to label those interactions that are considered high risk (potentially corrupt).

The social interaction measures include the calculation of high industry member transactions with a supervisor, with one staff member, with one staff member at different times of the day, with one staff member over different transaction types, more than two certificates of corrections in one day with one staff member, and a high percentage of transactions between an industry “bad actor” and a staff member.

Data:
One year of Qmatic data of all of the interactions between a respondent and a DOB staff member

