# Create Picture
Create new picture for advertisement.

### Request
```
GET /advertisements/{uuid}/pictures
```

### Headers
```
Accept: application/json
Authorization: Bearer ***********************
```

### Response
Status:
```
200
```
Body:
```
{
    "data": [
        "http://advertisement.homestead.app/image/300/150/picture-1.jpg",
        "http://advertisement.homestead.app/image/300/150/picture-2.jpg",
        "http://advertisement.homestead.app/image/300/150/picture-3.jpg",
        "http://advertisement.homestead.app/image/300/150/picture-4.jpg",
        "http://advertisement.homestead.app/image/300/150/picture-5.jpg",
    ]
}
```