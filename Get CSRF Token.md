# Get CSRF Token

Mendapatkan csrf token.

```
/sanctum/csrf-cookie
```

### Request

Method: ``GET``

Header:
- Accept : ``application/json``

### Response

Body: 
```json
{
	"status" : {
		"code" : 200,
		"success" : true,
		"message" : "<failed/success-message>"
	},
	"data" : []
}
```

