Documentation
=============

The ``League`` class
******************
.. autoclass:: League
    :members: league, sport, teams, conferences, baseUrl, currentGames

.. autofunction:: Rankings()

.. autofunction:: getNews()

The ``Team`` class
********************
.. autoclass:: Team
    :members: teamID, teamNickname, league, sport, baseUrl, schedule, conferenceID, subConferenceID, statistics, record, teamLogoURL

The ``Game`` class
********************
.. autoclass:: Game
    :members: gameID, league, sport, baseUrl, awayTeam, homeTeam, score, winProbabilityPercentage, winProbabilityTeam, spread, overUnder
