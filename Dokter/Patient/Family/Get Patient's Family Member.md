# Get Patient's Family Member

Mendapatkan data anggora keluarga dari pasien yang bersangkutan.

```
/api/user/{user_id}/families?pin={pin}
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

