# Login
User Authentication.

### Request
URI:
```bash
/login
```
Method:
```bash
Method: POST
```
Body Request:
```json
{
  "email": "user@domain.com",
  "password": "123456",
}
```

### Response
Status Code:
```bash
200
```
Body Response:
```json
{
  "name": "User Name",
  "email": "user@domain.com",
  "api_token": "************************************************************"
}
```