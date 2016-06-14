# Posts

## Get Posts with paging

> The response JSON structured for `status` post:

```json
{
  "meta": {
    "total": 6,
    "limit": 2,
    "page": 1
  },
  "data": [
    {
      "id": 51,
      "message": "Cron 2",
      "facebook_id": "478454982341646_532549640265513",
      "facebook_created_time": "2016-06-13 15:46:51 +0700",
      "facebook_updated_time": "2016-06-13 15:46:51 +0700",
      "facebook_post_type": "status",
      "created_at": "2016-06-13 17:32:50 +0700",
      "updated_at": "2016-06-13 17:32:50 +0700",
      "page": {
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
    },
    {
      ...
    }
  ]
}
```

> The response JSON structured for `photo` post:

```json
{
  "meta": {
    "total": 37,
    "limit": 2,
    "page": 1
  },
  "data": [
    {
      "link": "https://www.facebook.com/vinhnguyenduc.it.vn/photos/a.478458952341249.1073741827.478454982341646/532536066933537/?type=3",
      "object_id": "532536066933537",
      "full_picture": "https://scontent.xx.fbcdn.net/v/t1.0-9/q85/s720x720/13423901_532536066933537_8534472880852895771_n.jpg?oh=b1dfab1d2b9cf62b7942942329a9504d&oe=580F94F1",
      "id": 53,
      "message": "Hơi sương",
      "facebook_id": "478454982341646_532536066933537",
      "facebook_created_time": "2016-06-13 14:45:45 +0700",
      "facebook_updated_time": "2016-06-13 14:45:45 +0700",
      "facebook_post_type": "photo",
      "created_at": "2016-06-13 17:32:50 +0700",
      "updated_at": "2016-06-13 17:32:50 +0700",
      "page": {
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
      "photos": [
        {
          "id": 63,
          "width": 540,
          "height": 720,
          "parentable_id": "53",
          "parentable_type": "Post",
          "created_at": "2016-06-13 17:32:50 +0700",
          "updated_at": "2016-06-13 17:32:50 +0700",
          "resized_photos": [
            {
              "id": 387,
              "photo_id": 63,
              "width": 1536,
              "height": 2048,
              "created_at": "2016-06-13 17:32:50 +0700",
              "updated_at": "2016-06-13 17:32:50 +0700"
            },
            {
              ...
            }
          ]
        }
      ]
    },
    {
      ...
    }
  ]
}
```

> The response JSON structured for `video` post:

```json
{
  "meta": {
    "total": 3,
    "limit": 2,
    "page": 1
  },
  "data": [
    {
      "source": "https://video.xx.fbcdn.net/v/t42.1790-2/13262963_245998835791112_1789496047_n.mp4?efg=eyJ2ZW5jb2RlX3RhZyI6InN2ZV9zZCJ9&rl=664&vabr=369&oh=4dcd9765e249bdab5d07d1ea0df49a54&oe=5760DCFF",
      "name": null,
      "link": "https://www.facebook.com/vinhnguyenduc.it.vn/videos/523240997863044/",
      "object_id": null,
      "full_picture": "https://fbcdn-vthumb-a.akamaihd.net/hvthumb-ak-xft1/v/t15.0-10/s720x720/13178358_523241231196354_1010402047_n.jpg?oh=e5fde22a3918865cd5f7a696ce382adb&oe=57CFE919&__gda__=1477322409_ce75594fa46bc13f3b0afcc25e237829",
      "id": 58,
      "message": "test share own video",
      "facebook_id": "478454982341646_523242414529569",
      "facebook_created_time": "2016-05-18 22:21:23 +0700",
      "facebook_updated_time": "2016-05-18 22:21:23 +0700",
      "facebook_post_type": "video",
      "created_at": "2016-06-13 17:32:51 +0700",
      "updated_at": "2016-06-13 17:32:51 +0700",
      "page": {
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
      "photos": []
    },
    {
      ...
    }
  ]
}
```
> The response JSON structured for `link` post:

```json
{
  "meta": {
    "total": 2,
    "limit": 2,
    "page": 1
  },
  "data": [
    {
      "source": null,
      "name": null,
      "link": "http://mp3.zing.vn/album/Nhac-Hay-Nhat-Cua-Hoaprox-Hoaprox/ZWZCW7EW.html",
      "object_id": null,
      "full_picture": "https://fbexternal-a.akamaihd.net/safe_image.php?d=AQA17hH1mVr61DWB&url=http%3A%2F%2Fimage.mp3.zdn.vn%2Fcovers%2F3%2Fb%2F3b52d65a1cedaca4cbf00f0aa911d91e_1452848968.jpg",
      "id": 60,
      "message": "Test post mp3 link http://mp3.zing.vn/album/Nhac-Hay-Nhat-Cua-Hoaprox-Hoaprox/ZWZCW7EW.html",
      "facebook_id": "478454982341646_523240464529764",
      "facebook_created_time": "2016-05-18 22:12:20 +0700",
      "facebook_updated_time": "2016-05-18 22:12:20 +0700",
      "facebook_post_type": "link",
      "created_at": "2016-06-13 17:32:51 +0700",
      "updated_at": "2016-06-13 17:32:51 +0700",
      "page": {
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
      "photos": []
    },
    {
      ...
    }
  ]
}
```
This endpoint retrieves all specific posts type.

### HTTP Request

`GET {{base_url}}/api/v1/posts?facebook_post_type=?&page=?&limit=?&page_ids[]=?`

### Query Parameters

Parameter | Type | Required | Description
--------- | -------- | -------- | -----------
facebook_post_type | String |  | one of (`status` `photo` `video` `link`), default: `status`
page | Integer |  | The page index for paging
limit | Integer |  | Number of items for paging
page_ids[] | Integer | Yes | Can be multiple, ex: `page_ids[]=1&page_ids[]=2&page_ids[]=3`

### Error

HTTP Code | Server code | Message | Description
--------- | ----------- | ------- | -----------
400 | 1000 | The following param(s) are missed: page_ids | `page_ids[]` param is missed
400 | 1000 | Pagging out of scope!!! | Given total posts are 10. Then you pass `page=5` and `limit=5`.
