# Cleaning Chess Tournament Data with Minimal RegEx

The purpose this document is to describe the process of importing the data in `tournamentinfo.txt` and making it amenable to R.

Each record is a player in the chess tournament. Records include player ID, player state, total points, pre- and post-tournament rating, outcome of all rounds (seven total), the opponents' IDs for each match, and the color of the player that match.

The end goal is a clean dataframe with player name, player state, total points, pre-tournament rating, and average pre-tournament rating of opponents.

A supplementary analysis discusses how well associated ELO scores are with winning matches.