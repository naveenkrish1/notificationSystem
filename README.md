FRONT END:
   Front End contains the following pages:
               1.Homepage
               2.LoginPage
               3.RegisterPage
               4.Addcourses
               5.MyCourses
               6.Notifications
               
BACK END:
      Backend contains the following service
1.Login service:
 Endpointurl:/login
 MethodType:POST
          	checkLogin()
•	USERNAME
•	PASSWORD


2.Signup Service:
		EndpointUrl:/signup
		Methodtype:POST
     		createNewUser()
•	USERNAME
•	PASSWORD

3.AddcourseAPI:
                EndPointUrl:/addcourse
                Methodtype:POST
               AddCourse()
•	COURSEID
•	COURSENAME





4.RegistercourseAPI:
                   EndPointURL:/registercourse?username?courseid?coursename
  			Methodtype:POST
                   Registercourse()
•	USERNAME
•	COURSEID
•	COURSENAME
5.GetcoursesApi:
  		   EndpointURL:/getcourses?username
               Methodtype:POST
               Getcourses()
•	USERNAME
         	RETURNS:
•	COURSEID
•	COURSENAME



6.NotificationApi:
          		EndpointUrl:/notifications?username
                   MethodType:POST
                   Notifycourses()
•	USERNAME
RETURNS:
•	NOTIFICATIONS
•	STATUS
7.UpdateNotificationStatus:
                    ENDPOINTURL:/updatestatus
                     METHODTYPE:POST
Updatestatus()
•	notificationid
