Rounds
======

Get rounds
----------

* `GET /rounds.json` will return all rounds.

```json
[
  {
    "id": "1",
    "name": "Round of 64",
    "status": "active",
    "matchups": [
      {
        "home_team": {
          "id": "1",
          "name": "NYC",
          "seed": 3,
          "region": "East",
          "wins": 20,
          "loses": 30,
          "score": 90
        },
        "away_team": {
          "id": "2",
          "name": "Chicago",
          "seed": 4,
          "region": "East",
          "wins": 25,
          "loses": 25,
          "score": 100
        },
        "winner_team_id": "2",
        "starts_at": "2014-01-01T13:00:00-05:00",
        "created_at": "2014-01-01T13:00:00-05:00",
        "updated_at": "2014-01-01T13:00:00-05:00"
      }
    ]
  }
]
```

Get round
----------

* `GET /rounds/1.json` will return the specified round.
* `GET /rounds/current.json` will return the current round.

```json
{
  "id": "1",
  "name": "Round of 64",
  "status": "active",
  "matchups": [
    {
      "home_team": {
        "id": "1",
        "seed": 3,
        "region": "East",
        "wins": 20,
        "loses": 30,
        "score": 90
      },
      "away_team": {
        "id": "2",
        "seed": 4,
        "region": "East",
        "wins": 25,
        "loses": 25,
        "score": 100
      },
      "winner_team_id": "2",
      "starts_at": "2014-01-01T13:00:00-05:00",
      "created_at": "2014-01-01T13:00:00-05:00",
      "updated_at": "2014-01-01T13:00:00-05:00"
    }
  ]
}
```
