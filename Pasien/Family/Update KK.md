Tandai seseorang apakah masih 1 KK dengan user atau tidak.
User tidak bisa melihat informasi dari **saudara** (brother/sister) yang sudah berbeda KK.

```
/api/family/{family_id}
```

*Note: family_id -> id user dari anggota keluarga yang ingin diupdate.*
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
	"same_kk" : false
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

