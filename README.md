# Election-Analysis

Overview of the Election Audit
After recently assisting Tom and Seth with the election analysis, the election commission has asked for additional anlysis to be completed.  The current request is to supply three different items:

1. Voter turnout for each county
2. The percentage of votes from each county out of the total count
3. The county with the highest turnout

Election Audit Results

* How many votes were cast in the congressional election?

Across the voting district the total votes cast were 369,711.  We obtained this count by initializing a total vote counter and including this into a for loop to calculate the total votes cast.  It was then placed to print to the terminal and text file.  Images of the code included below:

https://github.com/JohnJohnson913/Election-Analysis/blob/09c6ea6fae6ee0de4bd553483857c1b86fc8d051/Resources/Total_Votes_Print.png

https://github.com/JohnJohnson913/Election-Analysis/blob/09c6ea6fae6ee0de4bd553483857c1b86fc8d051/Resources/Total_Votes_Variable.png

https://github.com/JohnJohnson913/Election-Analysis/blob/09c6ea6fae6ee0de4bd553483857c1b86fc8d051/Resources/Total_Votes_in_For_Loop.png

* Breakdown for the number of votes and the percentage of total votes for each county in the precinct:

We identify 306,055 total votes in Denver county, equating to 82.8% of election turnout in Denver county.  Followed by Jefferson county at 38,855 total votes (10.5%) and Arapahoe county at 24,801 or (6.7%) of total votes.

* Which county had the largest number of votes?

The percentage of votes per county indicated a very significant turnout for Denver county, likely due to it's urban/suburban nature and population density.   We identify 306,055 total votes in Denver county, equating to 82.8% of election turnout in Denver county.  This makes Denver county the with the largest number of votes.

* Provide a breakdown of the number of votes and percentage of total votes each candidate received

Charles Casper Stockham received 85,213 votes, this accounts for 23% of the total votes cast
Diana Degette received 272,892 votes, accounting for 73.8% of the total votes cast
Raymon Anthony Doane received 11,606 votes, accounting for 3.1% of total votes cast.
 
* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

This gives Diana Dagette a commanding lead in the election with 73.8% or 272,892 votes of the 369,711 total votes cast.  

Election-Audit Summary: In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

This script offers variability in many ways, two of which would be:

The ability to modify the script to account for additional or different counties by directing the script to identify candidates and vote counts.  The script could be modified to account for different counties by pointing the file to load to a different CSV file on the system.  In much the same way, teh script could be modified to index other lists of candidates for the new/added counties and ran to gather the same information for the different election.  The core code would remainly only slighty modified allowing for easy debugging if needed.  Finally, it could be modified to account for a different output location as well by modifying the save path.

Changing file to path image:  https://github.com/JohnJohnson913/Election-Analysis/blob/09c6ea6fae6ee0de4bd553483857c1b86fc8d051/Resources/File_to_Path.png

Changing save to path image:  https://github.com/JohnJohnson913/Election-Analysis/blob/09c6ea6fae6ee0de4bd553483857c1b86fc8d051/Resources/Path_to_Save.png

