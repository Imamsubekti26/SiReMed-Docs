Lorem Ipsum sit dolor

```
/api/?
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

