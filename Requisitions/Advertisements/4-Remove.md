# Remove a specific advertisement
Remove item of advertisement.

### Request
```
DELETE /advertisements/{uuid}
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