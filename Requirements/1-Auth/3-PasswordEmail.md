# Password Email
Send email to user with reset token.

### Request
```
POST /password/email
```

### Headers
```
Accept: application/json
```

### Parameters
```
email: required, type email, max 255
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
        "message": "We have e-mailed your password reset link!"
    }
}
```