# Edit Advertisement
Edit a specific advertisement for user.

### Request
```
PUT /advertisements/{uuid}
```

### Headers
```
Accept: application/json
Authorization: Bearer ***********************
```

### Parameters:
```
title: required, string, max:255
description: required, string
tags: required, string
price: required, numeric
```

### Response
Status:
```
200
```
Body:
```
{
    "data": {
        "uuid": "d567e618-6d7c-11e7-92fd-080027192ca4",
        "tags": "tag1,tag2,tag3",
        "title": "Title of Advertisement",
        "cover": "http://advertisement.homestead.app/image/300/150/no-picture.jpg",
        "price": 10000.00,
        "published": null,
        "description": "Description of Advertisement"
    }
}
```