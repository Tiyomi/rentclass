# Remove Picture
Remove specific picture for advertisement.

### Request
```
DELETE /advertisements/{uuid}/pictures/{file}
```

### Headers
```
Accept: application/json
Authorization: Bearer ***********************
```

### Response
Status:
```
204
```
Body:
```
{
    "data": [
        "http://advertisement.homestead.app/image/300/150/no-picture.jpg"
    ]
}
```