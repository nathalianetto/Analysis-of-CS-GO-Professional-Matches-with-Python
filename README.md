# ANALYSIS OF CS GO PROFESSIONAL MATCHES

## Analysis performed with the purpose of learning and practicing the use of Python for data manipulation and visualization, including descriptive analysis of the base and application of Pearson's chi-squared test for statistical inference.

Data source:

https://www.kaggle.com/mateusdmachado/csgo-professional-matches/code

## About the game:

Counter-Strike is a FPS (First-Person Shooter) game in which two teams of 5 players face each other in a matchup. The game retains the same gameplay concepts since its first version, which include a Terrorist side (TR) that is tasked to plant a bomb and have it detonate, and a Counter-Terrorist side (CT) that is tasked to defuse the bomb or prevent it from being planted. Both teams can also win a round by eliminating all players on the opposing team before the bomb is planted.

A standard game of Counter-Strike is a best of 30 rounds, the winning team being the first to win 16 rounds. The 30 rounds are played in two halves of 15 on each side of the map, with a round time limit of 1 minute 55 seconds, plus 40 seconds after the bomb is planted.

In case both teams draw at the 30th round on 15x15, 6 more rounds are added-on, which constitutes overtime. The overtime ends if a team wins 4 out of 6 rounds. If both teams win 3 rounds in overtime, another overtime of 6 rounds is played, and the process might repeat indefinitely until one team wins it.

There are 7 maps in the map pool that are available to be played competitively at any given time. Maps are removed and added frequently for updates and revamps, as to not make the game stale. Matches are normally played as a 'bo3' (Best of 3) maps, with less important matches played in a 'bo1' fashion and finals often played as 'bo5's.

## About the data:

The dataset contains 19 columns with the result of 45773 maps plays, including: date, first team, second team, the map, rounds won by each team, rounds won by the first and second team on each side (CT or TR), which team started as CT, match id, championship id, rank of each team and final result of the match.
