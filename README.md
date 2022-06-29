<h1>Lab: Working with Government Data</h1>

Choose a pubicly available dataset from a government entity. Use raw data/micro data, not data that has already been summarized.<br>
Try to find a dataset that's particulary interesting to you, and then find a column in the dataset that you want to study, and that is appropriate for a frequency chart. <br>

The data should be in a .xlsx, .sas7bdat, or .csv file (.zip data often contains these filetypes). <br>
Find the data dictionary or codebook that corresponds to your data file. (In rare cases, the file will contain descriptive info and no codebook is necsssary). <br>

Here are some sources of government data:

United States Census
https://data.census.gov/cedsci/
https://www.census.gov/programs-surveys/acs/microdata/access.html

Federal Reserve
https://www.federalreserve.gov/data.htm

Center for Disease Control & Prevention
https://www.cdc.gov/nchs/data_access/ftp_data.htm

Home Mortgage Disclosure Act
https://ffiec.cfpb.gov/data-publication/2021

National Center for Education Statistics
https://nces.ed.gov/


Navigating these data can be tricky, and is also part of a data scientist's job. <br><br>
In order to download the code for today's lab and modify it, CD into your class folder using the command line, then enter the following commands:

```
git clone https://github.com/CTDdata/govtDataLab
cd govtDataLab
jupyter notebook
```

The Jupyter Notebooks interface will open in your browser. You can open govt-data.ipynb and modify it to work for your dataset, which you will drag into the govtDataLab folder.

Modify and run the appropriate cells. When you are done, a frequency chart that reflects the appropriate column of your chosen dataset should appear at the bottom of the notebook. Save your work.

Create a new Github repository, and be sure to create a README.md file. Upload your modified Jupyter notebook to the repository, and in the README.md file, write at least 100 words about why the chosen dataset is interesting to you. Write about why you selected this column for a frequency analysis, and what the frequency chart has revealed. Save your changes, and turn in a link to your new Github repository. 

I should be able to see your outputs, including frequency chart, when I click into your Jupyter notebook in the Github browser (as in <a href = 'https://github.com/CTDdata/govtDataLab/blob/aces-output/govt-data.ipynb'>this example</a>). 

<h2>Potential Issues</h2>
<h3>Git problems</h3>
If the git command above doesn't work, try running the following first:

```
conda install -c anaconda git
```
<h3>Data Frustration</h3>
If you have tried multiple attempts with your chosen dataset and it isn't working, or if it can't work for this assignment, you can go to Schoology>Week 1>Day 3>Backup Dataset. At 16 MB, it is a relatively manageable file size. Choose a column to work with that you find interesting. 





