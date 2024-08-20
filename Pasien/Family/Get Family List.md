# Get Family List

Mendapatkan daftar anggota keluarga dari user yang login saat ini.

```
/api/families
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
		"members" : [],
		"pending_request" : [],
		"pending_confirm" : []
	}
}
```

*Body notes:* 
- *members : anggota keluarga yang sudah di verifikasi oleh kedua belah pihak.*
- *pending_request : ketika anda ingin memasukkan seseorang ke dalam keluarga, namun belum dikonfirmasi oleh yang bersangkutan.*
- *pending_confirm : ketika ada orang yang ingin memasukkan anda ke dalam keluarga, namun belum anda konfirmasi.*
