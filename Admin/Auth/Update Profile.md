# Update Profile

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
	"picture": "<base64-profile-picture>",
	"pin": "<pin>",
	"old_pin": "<old-pin>"
}
```

*Note: Old-pin is optional, only used when user want to update the existing pin*

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

