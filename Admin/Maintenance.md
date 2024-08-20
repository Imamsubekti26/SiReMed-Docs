# Maintenance (not full implemented yet)

*TODO: aktifkan 'down' bawaan laravel*

Hit sekali untuk pindah ke mode maintenance, hit sekali lagi untuk pindah ke mode ready.

```
/api/admin/system/maintenance
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
	"reason" : "<reason>"
}
```

*Note: hilangkan reason dari body ketika menonaktifkan mode maintenance*
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

