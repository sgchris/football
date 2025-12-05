# Ideas list

- players' scores (UEFA/FIFA)
  - total score for a team (opening + bench)
- players' market values
  - total team value + rival
- links to watch the game

- dashboard top bar with numbers/graphs
(place in the league(s))(latest score)(next game)

- chat/forum/discussion

- interesting games in the last/current league cycle

- blog containing an article after every game

- manager main tactics
  - tactics used in the last/current game
  - tactics that were used by the opponent

- show players who played in different positions

- show who played in the last game
  - who were substituted + by whom replaced
  - who played in the last game
  - who injured
  - got red/yellow card + whether that means something, like too many yellow
  or in case of a red card, was it direct or followed by a second yellow? Which matches
  he might miss

--------

# Pages

Description of the pages on the website

## homepage

The homepage consists of several parts. Looks like a dashboard, with 
sidebar with the commands, top bar with the high level stats, main area divided 
into two columns (the left one is slightly wider).

### Sidebar

Extendable sidebar with:

- authenticated user on the top
- favorite teams in the middle
- (settings in the bottom?)

### top

- bar with the stats of the team
  - Logo + Name / Manager name / Captain name / Home stadium
  - Leagues with positions
    - Place in the league table
    - Step + standing. E.g. for champions league, it could be:
      - "Group A, 2nd place"
      - "Playoffs, 1/8 Finals"
    - Total cost/fifa-rank

### Main area

- two panels
  - left panel
    - A photo of the latest or upcoming game (check if possible)
    - latest game (2 days after)
    (like in Google - Score, goals, events)
    - upcoming game (2 days before)
    - players participated in the game
    every player has: photo with colored borders, captain tag, flag (nationality),
    estimated net worth, FIFA score, "in the club since"/"acquired with $999K
    at June 2021"
      - goalkeeper
      - opening 10
      - substitutes who entered
      - remaining substitutes
    - Review of the game (like a newspaper article. Short (10-15 lines))
      - Analytics, hot moments, vibe. Use the [prompt](prompt_for_a_game).
  - right panel
    - injured players + estimated return to the games/club
    -
