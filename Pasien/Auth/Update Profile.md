# Update Profile (not tested yet)

update profile

```
/api/user
```

### Request

Method: ``PUT``

Header:
- Content-type : ``application/json``
- Accept : ``application/json``
- X-CSRF-TOKEN : ``<csrf-token>``
- Authorization : ``Bearer <access-token>``

Body: 
```json
{
	"email": "<new-email>",
	"phone": "<new-phone-number>",
	"address": "<new-address>",
	"picture": "<multipart-new-profile-picture>"
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

