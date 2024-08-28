# Bypass

Digunakan untuk mem-bypass maintenance mode

```
/{bypass_code}
```

### Request

Method: ``GET``

Header:
- Accept : ``application/json``
- Authorization : ``Bearer <access-token>``

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

