# verifyDD

This is a free bet fairness verifier for DuckDice.

DuckDice uses a mathematically verifiable algorithm to calculate the number roll outcomes of each of your bets.  This is done by taking a static server seed, a client seed (which you can customize) and the number (nonce) of each roll.  These three factors are taken into a mathematical algorithm to calculate your rolled number outcomes of each bet.

The goal of this verifier is to download your bet history from DuckDice, input the bet.csv file(s) downloaded and use this verifier to make sure DuckDice is not cheating any rolled number outcomes.

This code is entirely client side (meaning that all of the bet roll verifications are done in your web browser).  No information is gathered by or sent from this verifier.

This is a pre-release with more information and documentation to come.
