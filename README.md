## Election
# Python analysis of colorado electrion district results

# Overview
In order to better understand an election, I looked at the vote breakdown 3 counties in colorado 
Arapahoe, Denver, and Jefferson, and the 3 candidates who were in the race as well. 
Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. To analyze it, I used Python
to look into how the total votes from all three counties were distributed among the three candidates 
and how the total votes were distributed among the three counties. 
What I found was there were 369,711 votes overall, Denver county was the largest county in the data set
with 82.8% of the votes (306,055 total), Jefferson County followed with 10.5% and Arapahoe County rounded it out with 6.7%. 
It was also determined that Diana Degette won the election with 73.8% (272,892 total votes) of the vote. 
------------------------------------------------------
# What was done
* Took a csv with all vote data and used it for our analysis. 
 ![Initial steps](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(34).png)
  * The data was stored into a candidate list, and county dictionary with initial votes set to zero. 
  * A text file to save the analysis into was created as well called "election_analysis.txt".  
 
* ![Building Blocks](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(35).png)
  * Then, the county data for the largest turnout and winning candidate were set to an empty string and to zero votes. 
  * Then began the analyzation of the csv. First thing was using a with statement to bring the csv into python. 
  * After setting the header to be skipped, a for loop was used to go through each row of the csv and count it as one vote
  * Then the candidate and county information was extracted using the same for loop. 
* ![Building Blocks cont.](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(36).png)
  * After that, it was ensured that any data not in the county dictionary or candidate list was added into their respective slot. 
  * this was done using an if statement. 
  * At the end, it was ensured that the county information was properly counted in future analysis as well. 
* ![This is where the text begins](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(40).png) 
  * In this segment, all that was done was setting up the csv to be analyzed in the terminal. 
  * This is continued in the following screenshot, where it is then printed into the terminal and saved into its own text file. 
* ![Fun cont.](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(37).png)
  * The analysis in this part is a for loop that goes over the county dictionary to find how many votes each county recieved.
  * It then set those totals into a percentage, and printed the results into the terminal and saved it into the text file. 
  * We then started an if statment to look into the largest county. 
* ![The If statement](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(38).png)
  * Then the results were printed to the terminal and saved to the text file 
  * A for loop was then used to assess the candidates vote count and percentage. This was then printed to the terminal and saved. 
  * To find the winning candidate, we simply looked at who had the greatest number of votes out of the total vote count. 
* ![Finale](https://github.com/TCJester10/Election/blob/main/deliverable/Screenshot%20(39).png)
  * This then was printed to the terminal 
  * And of course saved into the text file. 
------------------------------------------------------
  

# Things that can done in the future

The first thing to I would do to expand on this is to look at the election results by county. 
To do this I would take each individual county race and analyze it like the total votes. 
This would give a more in depth look, and allow us to see where exactly the race was won. 
First, I would analyze the race in Arapaho by using the candidate list
and the for loop counting up the votes by candidate making sure it was 
looking at only votes cast in Arapaho.
After that, I would then do the same in Denver, and then Jefferson counties. 
This would give us a little more insight into how the election played out by county. 

We can also use this script for any election at any level. All that would need to be done is to 
change the parameters for the candidates and the counties to whichever election you are looking at. 
For example, if we wanted to look at the 2020 national election by state, all we would need to do is 
change the candidates to Joe Biden, Donald Trump, Jo Jorgenson, etc., and change the counties dictionary
into a dictionary of all 50 states. We could then perform the same analysis on the 2020 election. 
