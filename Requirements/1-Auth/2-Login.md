# Login
Check user authentication.

### Request
```
POST /login
```

### Headers
```
Accept: application/json
```

### Parameters
```
email: required, type email, max 255
password: required
```

### Response
Status:
```
200
```
Body:
```
{
  "name": "User Name",
  "email": "user@domain.com",
  "api_token": "************************************************************"
}
```