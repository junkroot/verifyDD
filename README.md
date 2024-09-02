# verifyDD

This is a free bet fairness verifier for DuckDice.

DuckDice uses a mathematically verifiable algorithm to calculate the number roll outcomes of each of your bets.  This is done by taking a static server seed, a client seed (which you can customize) and the number (nonce) of each roll.  These three factors are taken into a mathematical algorithm to calculate your rolled number outcomes of each bet.

The goal of this verifier is to download your bet history from DuckDice, input the bet.csv file(s) downloaded and use this verifier to make sure DuckDice is not cheating any rolled number outcomes.

This code is entirely client side (meaning that all of the bet roll verifications are done in your web browser).  No information is gathered by or sent from this verifier.

This is a pre-release with more information and documentation to come.

# Download bet histories from DuckDice

To download your bet history from DuckDice click on Profile, My bets, then click the drop down box in the top right hand corner.

Select "Manual & Auto Bets", pick a time frame ("All Period" is a good start) and click the Download button. 

Note: This verifier does not work with flash bet games or sports bets.

After some time, you will get a notification from DuckDice that your bet history is ready to be downloaded.  Click on this notification and download the zip file of your bet histories.

Unzip this bet histories zip file and you will find some (or many) CSV files named bets.csv, bets_1.csv, etc.  These are the bet CSV files that are needed to use this verifier.  Upload these bet CSV files (one by one, as many as you want to verify) into this verifier and click verify to see the results.

When the verifier finishes, it will update you with information of whether or not all of your bets were mathematically verified (or if some failed to be verified).

I plan to update this with more comprehensive documentation for users, but I'm just trying to get this verifier released for now.
