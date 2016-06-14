# Clubs
## All clubs

> The response JSON structured :

```json
{
  "meta": {
    "total": 2,
    "limit": 10,
    "page": 1
  },
  "data": [
    {
      "id": 3,
      "code": "lv",
      "name": "Livepool",
      "created_at": "2016-06-13 17:10:13 +0700",
      "updated_at": "2016-06-13 17:10:13 +0700"
    },
    {
      "id": 4,
      "code": "mu",
      "name": "Manchester United",
      "created_at": "2016-06-13 17:10:13 +0700",
      "updated_at": "2016-06-13 17:10:13 +0700"
    }
  ]
}
```

Retreive all clubs

### HTTP Request

`GET {{base_url}}/api/v1/clubs`
