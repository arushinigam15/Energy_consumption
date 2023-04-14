# Energy_consumption
This database is used as part of the study Open Source in Enviromental Sustainability. For this purpose, meta data from the listed repositories are evaluated via the tool AwesomeCure. To make browsing and sorting easier, here is the table with all the metadata for the projects and the related organizations. The CSVs file can be easily read into a Pandas DataFrame using the following code:

import pandas as pd

projects = 'https://raw.githubusercontent.com/protontypes/AwesomeCure/main/csv/projects.csv'
orgs = 'https://raw.githubusercontent.com/protontypes/AwesomeCure/main/csv/github_organizations.csv'

df = pd.read_csv(orgs)
df.head()
