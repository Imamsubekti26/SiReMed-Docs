# Family's Personal Info

Mendapatkan daftar record milik anggota keluarga
(hanya bisa diakses oleh anggota keluarga bersangkutan)

```
/api/user/{user_id}/records
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

