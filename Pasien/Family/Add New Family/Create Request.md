# Create Request

Lakukan permintaan untuk memasukkan seseorang menjadi anggota keluarga.

```
/api/family
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
    "user_id": "<id-family-member>",
    "relationship": "<relationship>",
    "same_blood":true,
    "same_kk": true
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

