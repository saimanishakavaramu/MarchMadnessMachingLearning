#Analyzing March Madness Winners with Machine Learning

Explanation of Variables:
    - Success of Team in March Maddness is evaluated by the amount of wins:
        0 - first round
        1 - second round
        2 - sweet sixteen
        3 - elite eight
        4 - final four
        5 - final
        6 - championship

    - Simple Rating System: 
        A rating that takes into account average point differential and strength of schedule. The rating is denominated in points above/below average, where zero is average. Non-Division I games are excluded from the ratings

    - Strength of Schedule:
        A rating of strength of schedule. The rating is denominated in points above/below average, where zero is average. Non-Division I games are excluded from the ratings

    - Pace Factor:
        An estimate of school possesion per 40 mins

    - Offensive Rating:
        An estimate of points scored (for teams) or points produced (for players) per 100 possessions

    - Free Throw Attempt Rate:
        Number of FT Attempts Per FG Attempt

    - Three-Point Attempt Rate:
        Percentage of FG Attempts from Three-Point Range

    - True Shooting Percentage:
        A measure of shooting efficiency that takes into account 2-point field goals, 3-point field goals, and free throws

    - Total Rebound Percentage:
        An estimate of the percentage of available rebounds a player grabbed while they were on the floor

    - Assist Percentage:
        An estimate of the percentage of teammate field goals a player assisted while they were on the floor

    - Steal Percentage:
        An estimate of the percentage of opponent possessions that end with a steal by the player while they were on the floor

    - Block Percentage:
        An estimate of the percentage of opponent two-point field goal attempts blocked by the player while they were on the floor

    - Effective Field Goal Percentage:
        This statistic adjusts for the fact that a 3-point field goal is worth one more point than a 2-point field goal

    - Turnover Percentage:
        An estimate of turnovers per 100 plays
        
    - Offensive Rebound Percentage:
        An estimate of the percentage of available offensive rebounds a player grabbed while they were on the floor
