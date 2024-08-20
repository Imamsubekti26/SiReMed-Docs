# Switch Account Role to Doctor (not tested yet)

Mengubah role pasien menjadi dokter.

```
/api/admin/user/{user_id}
```

### Request

Method: ``PATCH``

Header:
- Content-type : ``application/json``
- Accept : ``application/json``
- X-CSRF-TOKEN : ``<csrf-token>``
- Authorization : ``Bearer <access-token>``

Body: 
```json
{
	"role": "doctor",
	"nip": "<nip-number>"
}
```

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

