# Get Nonactive Doctor List

Mendapatkan daftar user yang telah nonaktif dengan role doctor.

```
/api/admin/users?role=doctor&only_delete=1
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

