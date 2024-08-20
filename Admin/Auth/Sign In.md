# Sign In

Login untuk admin

```
/api/admin/login
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
	"email" : "<your-email>",
	"password" : "<password>",
	"remember" : false
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

