# Me
Update profile of user

### Request
```
PUT /me
```

### Headers
```
Accept: application/json
```

### Parameters
```
name: required, string, max 255
email: required, string, type email, max 255, unique
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
        "message": "Your password has been reset!"
    }
}
```