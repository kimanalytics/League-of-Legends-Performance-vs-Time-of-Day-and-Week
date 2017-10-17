# League of Legends Performance vs Time of Day and Week

Gaming. Do we perform the best during the day or night? After work or before work? During work? This quick study uses Riot's API to find out.

## Motivation
The field of eSports is rapidly taking over the entertainment industry with over 100 million monthly players for League of Legends.

This movement has gotten so serious to the point where universities such as UC Irvine are offering scholarships to top gamers. With this, many gamers are seeking to improve and train for games such as League of Legends similar to how student athletes train to get better at sports.

So how do players improve performance or in gaming terms, "git gud"?

## Introduction
Analytics sites such as Mobalytics and OP.GG help users gain insights on how to improve their game play so that they can win more games.

## Performance vs Time of Day/Week
Something that isn't answered by many analytic sites is performance versus time of day.

For example, we all have a preferred time of day to do thing such as work, study, and sleep. Perhaps we perform the best during the day, thus we work during that time. Maybe we study in the afternoon since that is when or coffee has kicked in. Also, maybe we sleep during the night since our body's performance is the weakest then.

What about gaming performance? Do we perform the best during the day or night? After work or before work? During work? This quick study uses Riot's API to find out.

## Methods
The method we are going to use for this study is requests on Riot's API. For this, we use a developer API key. Limitations to this method is that the API code will expire in a day and also is limited to 100 requests per 2 minutes. Thus, we will limit data to 100 games.

## Conclusion
For this player, here are the best and worst times to play.

The best times for this player to play is 5, 16, 20, and 21. (5 AM, 4 PM, and 8-9 PM.)
They win 10% more games than their average wins.

The worst time for this player to play is 3, 14, 17, and 22. (3 AM, 2 PM, 5 PM, and 10 PM)
They lose 10% more games than their average wins.

The best days of the week for this player to play is Tuesday and Saturday.
They win 10% more games than their average wins.

The worst days of the week for this player to play is Wednesday and Friday.
They lose 10% more games than their average wins.

## Discussion
To improve this study, here are some things that could be done.
- Larger than 100 sample size.
  - Although 100 games seems adequate for this study, more games is always better.
  - To achieve this, we need to apply for a better API key through Riot's development portal.
- KDA analysis
  - I've implemented a KDA algorithm in this study but did not use it.
  - League of Legends is a team game. Thus, performance may be affected by teammate's performances.
  - So instead of win rate, we could use KDA instead.
