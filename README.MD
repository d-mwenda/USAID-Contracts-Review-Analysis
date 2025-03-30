# DOGE Review of USAID Contracts Review

## Summary
We begin from this 284 page pdf memo dated **March 24, 2025** from one Ryan Shrum, Senior Advisor for Legislative and Congressional Affairs, to the congress,  with the subject **Update on USAID Financial and Personnel Status as of March 21, 2025**.

The first 3 pages of the memo give a summary of the personnel employment status and program overview. The rest of the pages list the outcome of the review of all USAID contracts. Out of the 284 pages, 278 are 2 long tables of the continuing and terminated contracts, alongside the names of the implementing organizations, description, contract value, contract dates and issuing offices. 
The tables contained the following columns:
- Award ID
- Contract PIID
- Vendor Name
- Contract Description
- Total Estimated Cost
- Oblibated Amount
- Contract State Date
- Contract End Date
- Issuing Office

This looked like a good amount of data to get various insights from. So I went down the rabit hole.

## Approach
ETL and analysis
1. Strip narratives and non-table data
2. Convert pdf to a spreadsheet
3. Clean and enrich the data programatically
4. Load and transform in Power BI
5. Analyse and publish
6. Continual improvement of all the steps.


### Step 0: Prep the stage
Create a virtual python environment

### Step 1: String narratives