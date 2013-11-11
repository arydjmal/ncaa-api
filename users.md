Users
=====

Get user
--------

* `GET /users/me.json` will return the current user.

```json
{
  "id": "1",
  "lucie_id": "1",
  "status": "active",
  "seed_count": 33,
  "picks": [
    {
      "team_id": "1",
      "round_id": "1",
      "matchup_id": "1",
      "created_at": "2014-01-01T13:00:00-05:00",
      "updated_at": "2014-01-01T13:00:00-05:00"
    },
    {
      "team_id": "2",
      "round_id": "1",
      "matchup_id": "1",
      "created_at": "2014-01-01T13:00:00-05:00",
      "updated_at": "2014-01-01T13:00:00-05:00"
    },
    {
      "team_id": "3",
      "round_id": "1",
      "matchup_id": "1",
      "created_at": "2014-01-01T13:00:00-05:00",
      "updated_at": "2014-01-01T13:00:00-05:00"
    }
  ],
  "created_at": "2014-01-01T13:00:00-05:00",
  "updated_at": "2014-01-01T13:00:00-05:00"
}
```
