# Remove Family

Menghapus seseorang dari daftar anggota keluarga.

```
/api/family/{family_id}
```

*Note: family_id -> id user dari anggota keluarga yang ingin dihapus.*
### Request

Method: ``DELETE``

Header:
- Accept : ``application/json``
- X-CSRF-TOKEN : ``<csrf-token>``
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
	"data" : []
}
```

