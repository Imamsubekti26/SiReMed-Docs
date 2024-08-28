# Documentation for SIReMed

SIRemed = Sistem Informasi Rekam Medis

Ini merupakan dokumentasi sekaligus API Contract untuk Backend Sistem Informasi Rekam Medis.

## Daftar Isi:

- Admin
	- Admin
		- Add new admin
		- Get admin list
	- Auth
		- Get Profile
		- Sign In
		- Sign Out
		- Update Profile
	- Doctor
		- Confirm doctor registration
		- disable & enable doctor account
		- get doctor list
		- get disabled doctor list
		- switch role from doctor to patient 
	- Maintenance
		- bypass maintenance
		- enable & disable maintenance mode
	- Patient
		- Disable & enable patient account
		- Get disabled patient list
		- Get patient list
		- switch role from patient to doctor
- Dokter
	- Auth
		- Get Profile
		- Sign In
		- Sign Out
		- Update Profile
	- Patient
		- Push New Data
			- New OCR
			- New Record
		- Get Patient's Record Info
		- See Patient's Lab Info
		- See Patient's Record Detail
- Pasien
	- Auth
		- Get Profile
		- Sign In
		- Sign Out
		- Update Profile
	- Family
		- Add New Family
			- Accept Request
			- Cancel Request
			- Create Request
			- Reject Request
		- Family's Info
			- Family's Member Info
			- Family's Personal Info
			- Family's Record Info
		- Get Family List
		- Remove Family
		- Update KK
	- Record
		- Get record list
		- See lab result
		- See record detail