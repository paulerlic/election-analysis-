# Election Audit Overview
  ### The purpouse of this audit is as follows:
   1. Help Seth and Tom submit the election audit results to the election commission.
   2. Determine a winner for the election. 
   3. Determine the voter turnout for each county.
   4. Determine the percentage of votes from each county out of the count. 
   5. Determine which county had the highest turnout.


# Election Audit Results


* How many votes were cast in this congressional election?  

  - The total number of votes cast is 369,711 votes.

![Total Votes](https://github.com/paulerlic/election-analysis-/blob/main/Election_Analysis-main/Election_Analysis/Resources/Total%20Votes.png)

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

    - The County Votes are as follows:
          Jefferson: 10.5% (38,855)
          Denver: 82.8% (306,055)
          Arapahoe: 6.7% (24,801)
          
![County Breakdown](https://github.com/paulerlic/election-analysis-/blob/main/Election_Analysis-main/Election_Analysis/Resources/County%20Votes.png)

* Which county had the largest number of votes?

  - The county with the largest number of votes was Denver! 
  
 ![Largest Votes by county](https://github.com/paulerlic/election-analysis-/blob/main/Election_Analysis-main/Election_Analysis/Resources/Largest%20County%20Turnout.png)
  
* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

  - In first place we have Diana DeGette with 272,892 votes, DeGette's votes represent 73.8% of the total votes. In second place we have Charles Casper Stockham with 85,213 votes, Stockham's votes represent 23.0% of the total votes. In third place we have Raymon Anthony Doane with 11,606 votes, Doane's votes represent 3.1% of the total votes. 

 ![Vote Count + % for canidates](https://github.com/paulerlic/election-analysis-/blob/main/Election_Analysis-main/Election_Analysis/Resources/Canidate%20Breakdown.png)

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

  - The winner of this fine election was Diana DeGette with 272,892 votes. This was an impressive victory Diana DeGette managed to secure 73.8% of the votes in a landslide victory. 

 ![Winner Winner Chicken Dinner](https://github.com/paulerlic/election-analysis-/blob/main/Election_Analysis-main/Election_Analysis/Resources/Winner.png)
 
 # Election-Audit Summary
 
  ### Proposal
  - Tom and Seth helped me to develope a very powerful easy to use script that analyze voting data for elections. Aside from being easy to use and powerful the script is also very flexible and can be modified to look for patterns and other siginificant statistics. Addtionally adding more data into the analysis could provide us with a much clearer picture of voting patterns in Colorado. 
    
  ### Modification #1
  
  - This script can easily be modified to output information telling us which county voted for which candidate, and what percentage of that counties vote went to each particular canidate. This can be done by modifying the county voting output to include a count and percentage of votes for each candidate by county. This information would be very useful in determing where a canidate should foucs campaigning efforts. 

  ### Modification #2
  
  - Another change to the script that we can make is improving the report of voter turnout by county. Instead of just listing the county with the largest turnout of voters we could list all of them. This would allow us to see what counties have the lowest turnout of voters. This information is critical for directing campaign efforts and will allow canidates to focus on either improving low voter turn out counties or avoiding counties where turn out rates are poor. 

  ### Modification #3
  
  - Although this modification requires adding addtional informtion to the analysis it would prove to be a very powerful addition. If we were able to get an accurate count of County populations in Colorado, we could add this information into the analysis by importing another CSV file with county populations and compare voter turnout, and county population. Having this information would tell us which counties have highest percentage of votes up for grabs. Most likley this would show us that the larger counties have more potential votes. However it would also allows us to know which other counties to focus on in campaigning becuase we would know if the turnout of voters vs the population was high or low. With this current script we have no way of knowing how county size impacts voter trunout because we do not have population information for the counties in the analysis.   









