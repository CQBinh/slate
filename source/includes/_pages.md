# Pages
## All pages for specific club

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
      "facebook_id": "478454982341646",
      "name": "Vinh.nguyen.it",
      "created_at": "2016-06-13 17:10:13 +0700",
      "updated_at": "2016-06-13 17:10:13 +0700",
      "club": {
        "id": 3,
        "code": "lv",
        "name": "Livepool",
        "created_at": "2016-06-13 17:10:13 +0700",
        "updated_at": "2016-06-13 17:10:13 +0700"
      }
    },
    {
      "id": 4,
      "facebook_id": "675477879173728",
      "name": "HelloWorld",
      "created_at": "2016-06-13 17:10:13 +0700",
      "updated_at": "2016-06-13 17:10:13 +0700",
      "club": {
        "id": 3,
        "code": "lv",
        "name": "Livepool",
        "created_at": "2016-06-13 17:10:13 +0700",
        "updated_at": "2016-06-13 17:10:13 +0700"
      }
    }
  ]
}
```

Retreive all pages in specific club

### HTTP Request

`GET {{base_url}}/api/v1/pages?club_id=?`

### Query Parameters

Parameter | Type | Required | Description
--------- | -------- | -------- | -----------
club_id | Integer | X | Club's id

### Error

HTTP Code | Server code | Message | Description
--------- | ----------- | ------- | -----------
400 | 1000 | The following param(s) are missed: club_id | `club_id` param is missed
404 | 404 | Couldn't find Club with 'id'=xxx | `club_id` is invalid

## Page's detail

> The response JSON structured :

```json
{
  "id": 3,
  "facebook_id": "478454982341646",
  "name": "Vinh.nguyen.it",
  "created_at": "2016-06-13 17:10:13 +0700",
  "updated_at": "2016-06-13 17:10:13 +0700",
  "club": {
    "id": 3,
    "code": "lv",
    "name": "Livepool",
    "created_at": "2016-06-13 17:10:13 +0700",
    "updated_at": "2016-06-13 17:10:13 +0700"
  }
}
```

Retreive page's detail

### HTTP Request

`GET {{base_url}}/api/v1/pages/{id}`

### Query Parameters

Parameter | Type | Required | Description
--------- | -------- | -------- | -----------
id | Integer | X | Page's id

### Error

HTTP Code | Server code | Message | Description
--------- | ----------- | ------- | -----------
404 | 404 | Couldn't find Page with 'id'=xxx | `id` is invalid
