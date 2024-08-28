# New Record Data

Menambahkan record baru untuk pasien terkait.

```
/api/record
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
	"hospital_id": "<hospital-id>",
	"department": "<department-name>",
	"note": "<note>",
	"vital_sign": {
		"heart_rate": 80,
		"temperature": 37,
		"respiratory_rate": 20,
		"blood_pressure": "80/100",
		"oxygen_levels": 98
	},
	"medicine": [
		{
			"name": "paracetamol",
			"dose": "500mg",
			"after_meal": true,
			"user_up": false,
			"hours": 8
		}
	],
	"food_allergies": [],
	"drug_allergies": ["penicilin"]
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

