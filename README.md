# COVID-19 Nigeria States Full Dataset
Last Updated: 9 May 2020

## About
This dataset contains the official daily data for COVID-19 cases in Nigeria broken down by state. To our knowledge this is the most complete COVID-19 dataset for Nigeria at this time.

## Why
We worked on this dataset because as budding data scientists, we couldn't find a suitably up to date and accessible dataset for COVID-19 and Coronavirus cases in Nigeria broken down by state to aid data scientists, statisticians and machine learning enthusiasts and experts in their analysis and search for solutions.

Although the Nigeria Center for Disease Control (NCDC) generates and publishes this data, it does so in PDF form which is not an easily accessible medium for automated methods and common data extraction libraries.


## Method
The original data is provided by the NCDC at https://bit.ly/covidncdc

The work being done by us is to extract the data from the PDF files into CSV format.

We tried to automate the extraction process using python (pandas with selenium and beautifulsoup) but did not succeed.

So we ended up doing it manually. And this means we have to keep updating the files manually (See the start of this write-up for the date of the most recent update.) 

## Folder Information
When you unzip the zip file, the structure of the folders are: 
- /PDF
- /CSV

Each of these folders contains the daily pdf and csv files placed in separate folders for each month.
 
The /PDF folder contains the original PDF data files downloaded from the NCDC website.

The /CSV folder contains the extracted daily data in CSV format. Each day has a separate file. The CSV files are named according to their date in the following format: dd_mm_yyyy.csv

## Missing Dates:
There was no published data for some of the days so there are no datafiles for those missing dates which are: 
- 20 March 2020
- 27 March 2020

## Data Source:
Nigeria Center for Disease Control (NCDC) https://ncdc.gov.ng/ 
Direct link to data page: https://bit.ly/covidncdc

## Credits:
- Tony Areghan => Ideas, time and effort 
- @shirts_ml on Twitter (https://twitter.com/shirts_ml) => Time and effort
- https://datamouse.blogspot.com => Time and effort
- NG44 Consulting https://ng44.com => Funding

## COVID-19 News Updates
https://coronavirusnigeria.ng4n.com/updates/

## Contact Us
For feedback send email to covid19data @ ng4n.com
