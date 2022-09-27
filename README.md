# Hispanic_candidates_NC
Hispanic candidates in North Carolina for the Nov. 2022 election.  

## The News & Observer did this project to obtain a statewide list of all Hispanic or Latino candidates on the ballot in the Nov. 2022 election. 

The News & Observer did this project to obtain a statewide list of all Hispanic or Latino candidates on the ballot in the November 2022 election.

The N&O obtained this list of candidates by joining the North Carolina State Board of Elections' current 'Statewide Voter Registration' database with its '2022 Candidate List Spreadsheet (CSV) (with email addresses)' database.

The candidate list database does not include what ethnicity candidates identify with, while the voter registration database does. This merging of databases shows which candidates identified as Hispanic or Latino in their voter registration.

To view the final list of candidates you can open the file 'final-results-hl-candidates-nov-22.csv' linked in this project or clone this repository.

The merge of databases is done via "fuzzy matching" on the names column with a .1 match system, which means some of the candidates listed in this CSV. file are not exact matches. This was done to allow room for any typos or slight discrepancies between how candidates listed their names on the candidate list vs. the voter rolls.

This does mean there may be some matches that should not be included in the final count. For the final tally we used at The N&O we manually verified the matches in the CSV. file before including them in the final list. 

Some caveats: This list is meant to be comprehensive but may leave out Hispanic or Latino candidates if they did not include their ethnicity in their voter registration.

## Download the databases
Before you run the code, make sure to first download the needed databases.  

Download link for NC voters database :  https://s3.amazonaws.com/dl.ncsbe.gov/data/ncvoter_Statewide.zip
Obtained 09/12/2022 from: https://www.ncsbe.gov/results-data/voter-registration-data 
The database I used was Statewide Voter Registration (ZIP) 

Download link for NC candidates for nov. 2022 election:  https://s3.amazonaws.com/dl.ncsbe.gov/Elections/2022/Candidate%20Filing/Candidate_Listing_2022.csv 
Obtained 09/12/2022 from: https://www.ncsbe.gov/results-data/candidate-lists#current
The database I used was 2022 Candidate List Spreadsheet (CSV) (with email addresses) 

## Unzip NC voters
You will need to unzip the NC voters database prior to uploading it into this directory. 
