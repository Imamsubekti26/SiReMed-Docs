# Get Patient's Personal Info

Mendapatkan data Informasi/profile dari pasien yang bersangkutan.

```
/api/user/{user_id}
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

