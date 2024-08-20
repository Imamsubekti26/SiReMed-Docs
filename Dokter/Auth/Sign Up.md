# Sign Up

Registrasi untuk role dokter dan pasien

```
/api/register
```

### Request

Method: ``POST``

Header:
- Content-type : ``application/json``
- Accept : ``application/json``
- X-CSRF-TOKEN : ``<csrf-token>``

Body: 
```json
{
	"name" : "<full-name>",
	"email" : "<email>",
	"password" : "<password>",
	"password_confirmation" : "<password>",
	"date_of_birth": "YYYY-MM-DD",
	"is_male": true,
	"address": "<address>",
	"phone": "<phone-number>",
	"nip": "<nip-number>"
}
```

*Note : hilangkan nip di dalam body jika ingin mendaftar sebagai pasien
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

