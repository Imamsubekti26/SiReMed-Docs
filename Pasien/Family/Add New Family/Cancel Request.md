Batalkan permintaan untuk memasukkan seseorang sebagai anggota keluarga.

```
/api/family/{family_id}
```

*Note: family_id -> id user dari anggota keluarga yang ingin dibatalkan.*
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
	"action" : "cancel"
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

