# New OCR Data (not implemented)

Input OCR baru untuk pasien terkait.

```
/api/ocr
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
	"patient_id": "<patient-id>",
	"hospital": "<hospital-name>",
	"department": "<department-name>",
	"date": "<ocr-taken-date>",
	"time": "<ocr-taken-time>",
	"note": "<note>",
	"ocr_file": "<multipart-file>"
	
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

