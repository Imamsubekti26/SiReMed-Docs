# Switch Account Role to Patient (not tested yet)

Mengubah role dokter menjadi pasien biasa.

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
	"role": "patient"
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

