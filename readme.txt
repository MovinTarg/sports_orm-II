Optional Assignment: Sports ORM II
Complete the following queries using the sports_orm and display the results on index.html.

This is the second part of the Sports ORM assignment. Note that, in the models, every player has exactly one .curr_team, and every team has exactly one .league. Modify apps/leagues/views.py and/or apps/leagues/templates/leagues/index.html so that when you start the server, the index page shows:

...all teams in the Atlantic Soccer Conference
...all (current) players on the Boston Penguins
...all (current) players in the International Collegiate Baseball Conference
...all (current) players in the American Conference of Amateur Football with last name "Lopez"
...all football players
...all teams with a (current) player named "Sophia"
...all leagues with a (current) player named "Sophia"
...everyone with the last name "Flores" who DOESN'T (currently) play for the Washington Roughriders
...all teams, past and present, that Samuel Evans has played with
...all players, past and present, with the Manitoba Tiger-Cats
...all players who were formerly (but aren't currently) with the Wichita Vikings
...every team that Jacob Gray played for before he joined the Oregon Colts
...everyone named "Joshua" who has ever played in the Atlantic Federation of Amateur Baseball Players
...all teams that have had 12 or more players, past and present. (HINT: Look up the Django annotate function.)
...all players and count of teams played for, sorted by the number of teams they've played for