
## NFL Fantasy Metrics

I've always been curious about the NFL. I remember spending many Sunday afternoons watching games with my dad, who was a huge fan of the Green Bay Packers and Pittsburgh Steelers. At the time, I thought the game was pretty complex and couldn't really grasp all the details. But in the last few years, I've gotten back in touch with the sport as my boyfriend enjoys playing NFL Fantasy and watching the NFL games in general, and now there's also an international game in Germany.

In a nutshell, NFL Fantasy is a virtual game where you can create leagues with friends and build your own team to compete against each other. The challenge is knowing which players to draft, and that decision can be based on a variety of variables - or sometimes just a gut feeling. In this article, I've put together a simple analysis of the metrics available in the latest NFL Fantasy data.

Each player in NFL Fantasy is assigned fantasy points. These points are calculated using specific formulas that can vary depending on the league you're in. In theory, the higher the fantasy points, the better the player's recent performance. The goal of my analysis is to determine which metrics contribute to a player earning more fantasy points. I've also calculated some additional metrics that can help you decide if a player is worth adding to your roster. Keep in mind that this is a very simple analysis that only includes historical metrics for the current season, and you will usually need to consider a number of external factors to make a decision on your player choices.

---
### Data

For this analysis, I'm using the Player Fantasy Ranks data from the Pro Football Reference site. It contains the fantasy rankings for the top ~500 players in the current 2024 season. Below is a description of the metrics included in the dataset:

+ Player Info:
    - Player name
    - Tm: Team
    - FantPos: Fantasy Position
    - Age, Games Played (G), Games Started (GS)

+ Passing Stats:
    - Attempts (Att), Completions (Cmp), Passing Yards (Yds), Passing Touchdowns (TD), Interceptions (Int)

- Rushing Stats:
Rushing Attempts (Att), Rushing Yards (Yds), Yards per Attempt (Y/A), Rushing Touchdowns (TD)

- Receiving Stats:
Targets (Tgt), Receptions (Rec), Receiving Yards (Yds), Yards per Reception (Y/R), Receiving Touchdowns (TD)

- Fumbles:
Fumbles (Fmb), Fumbles Lost (FL)

- Scoring Stats:
Total Touchdowns (TD), 2-Point Conversions Made (2PM)

- Fantasy Points:
Fantasy Points (FantPt), Points per Reception (PPR), DraftKings Points (DKPt), FanDuel Points (FDPt), Value-Based Drafting Score (VBD), Position Rank (PosRank), Overall Rank (OvRank)


---
### This is a header

#### Some T-SQL Code

```tsql
SELECT This, [Is], A, Code, Block -- Using SSMS style syntax highlighting
    , REVERSE('abc')
FROM dbo.SomeTable s
    CROSS JOIN dbo.OtherTable o;
```

#### Some PowerShell Code

```powershell
Write-Host "This is a powershell Code block";

# There are many other languages you can use, but the style has to be loaded first

ForEach ($thing in $things) {
    Write-Output "It highlights it using the GitHub style"
}
```

