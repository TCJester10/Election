## Election
# Python analysis of colorado electrion district results

# Overview
In order to better understand an election, I looked at the vote breakdown 3 counties in colorado 
Arapahoe, Denver, and Jefferson, and the 3 candidates who were in the race as well. 
Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. To analyze it, I used Python
to look into how the total votes from all three counties were distributed among the three candidates 
and how the total votes were distributed among the three counties. 
------------------------------------------------------
# What was done
* Took a csv with all vote data and stored the data 
  * The data was then stored into a candidate list, and county dictionary. 
 
* Used Python to store the voting data and sort it
  * First, it was sorted by votes by candidate
  * Then, it was sorted into votes by county where we found the largest county 

------------------------------------------------------
  

# Things that can done in the future

The first thing to I would do to expand on this is to look at the candidate results by county. 
To do this I would take each individual county race and analyze it like the total votes. 
First, I would analyze the race in Arapaho by using the candidate list
and the for loop counting up the votes by candidate making sure it was 
looking at only votes cast in Arapaho
After that, I would then do the same in Denver, and then Jefferson counties. 
This would give us a little more insight into how the election played out by county. 

We can also use this script for any election at any level. All that would need to be done is to 
change the parameters for the candidates and the counties to whichever election you are looking at. 
For example, if we wanted to look at the 2020 national election by state, all we would need to do is 
change the candidates to Joe Biden, Donald Trump, Jo Jorgenson, etc., and change the counties dictionary
into a dictionary of all 50 states. We could then perform the same analysis on the 2020 election. 
