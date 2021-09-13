# task_001
API :	[post][127.0.0.1:8000/Login]
API desc:
Login: This API access 2 parameters
User_name and password along with authentication code

API :[get][127.0.0.1:8000/Logout]
API desc:
	Logout: Logout API is checking whether is used under session control unit
	If user exits can logout from the session once after logout, we are saving logout datetime to the user.
  
API : [post][127.0.0.1:8000/register]
API desc:
	Register: It accepting 5 parameters
	1. name
	2.user_name
	3.password
	4.mobile
	5.email
	try to save that student data into student account file
  
 API: [get][127.0.0.1:8000/data]
 API desc:
  data:	We try to show
	login_count
	logout_count    particular users.
