# Register

Creating new users.


### Request

URI:
```bash
/register
```

Method:
```bash
Method: POST
```

Body Request:
```json
{
  "name": "Name User",
  "email": "user@domain.com",
  "password": "123456",
  "password_confirmation": "123456"
}
```


### Response

Status Code:
```bash
201
```

Body Response:
```json
{
  "message": "ok"
}
```