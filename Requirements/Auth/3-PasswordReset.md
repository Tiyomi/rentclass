# Password Reset
Reset user password.

### Request
```
POST /password/reset
```

### Headers
```
Accept: application/json
```

### Parameters
```
email: required, string, type email, max 255, unique
token: required, string
password: required, string, min 6, confirmed
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