Mendapatkan daftar record dan ocr

```
/api/records
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
	"data" : {
		"medical_record" : [],
		"ocr" : []
	}
}
```

