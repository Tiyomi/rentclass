# Create Picture
Create new picture for advertisement.

### Request
```
POST /advertisements/{uuid}/pictures
```

### Headers
```
Accept: application/json
Authorization: Bearer ***********************
```

### Parameters:
```
file: required, file, mimes-types (jpeg,jpg,png)
```

### Response
Status:
```
201
```
Body:
```
{
    "data": [
        "http://advertisement.homestead.app/image/300/150/no-picture.jpg"
    ]
}
```