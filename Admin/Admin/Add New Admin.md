# Add New Admin

Registrasi untuk admin

```
/api/admin/register
```

### Request

Method: ``POST``

Header:
- Content-type : ``application/json``
- Accept : ``application/json``
- X-CSRF-TOKEN : ``<csrf-token>``
- Authorization : ``Bearer <access-token>`` 

Body: 
```json
{
	"name" : "<full-name>",
	"email" : "<email>",
	"password" : "<password>",
	"password_confirmation" : "<password>"
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

