Picks
=====

Get picks
---------

* `GET /rounds/1/picks.json` will return user picks for the specified round.

```json
[
  {
    "id": "1",
    "name": "NYC",
    "seed": 3,
    "region": "East",
    "wins": 20,
    "loses": 30
  },
  {
    "id": "2",
    "name": "North Carolina",
    "seed": 4,
    "region": "East",
    "wins": 25,
    "loses": 25
  },
  {
    "id": "3",
    "name": "Miami",
    "seed": 5,
    "region": "East",
    "wins": 25,
    "loses": 25
  }
]
```

Create picks
------------

* `POST /rounds/1/picks.json` will add the new picks to the specified round from the parameters passed.

```json
{
  "picks": [
    {
      "round_id": 1,
      "matchup_id": 1,
      "team_id": 1
    },
    {
      "round_id": 1,
      "matchup_id": 2,
      "team_id": 2
    },
    {
      "round_id": 1,
      "matchup_id": 3,
      "team_id": 3
    }
  ]
}
```

Update picks
------------

* `PUT /rounds/1/picks.json` will update the picks from the parameters passed.

```json
{
  "picks": [
    {
      "round_id": 1,
      "matchup_id": 1,
      "team_id": 1
    },
    {
      "round_id": 1,
      "matchup_id": 2,
      "team_id": 2
    },
    {
      "round_id": 1,
      "matchup_id": 3,
      "team_id": 3
    }
  ]
}

```
