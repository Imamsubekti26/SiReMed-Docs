# Disable Enable Doctor (not tested yet)

Nonaktifkan akun dokter (jika aktif), Aktifkan akun dokter (jika nonaktif).

```
/api/admin/user/{doctor_id}
```

### Request

Method: ``DELETE``

Header:
- Content-type : ``application/json``
- Accept : ``application/json``
- X-CSRF-TOKEN : ``<csrf-token>``
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

