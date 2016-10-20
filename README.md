##Ticket Service Homework
A ticket service management for theater.

Implementation of a simple ticket service that facilitates the discovery, temporary hold, and final reservation of seats within a high-demand performance venue.
This application is developed using Spring Boot, Spring JDBC, Spring RESTful web services, Maven, HSQLDB.
###Assumptions

1.	Theatre has sitting arrangement based on levels.
2.	Seat provided based on availability. 
3.	User can choose levels (Orchestra, Mezzanine, Balcony[we can increase level by avoiding multiple changes]). Seats are assigned in each level as first come first serve bases.
4.	Hold time for the seats is 2 minute which can be updatable. If the user doesn't reserve the seats before 2 minute, then the holds are removed and user has to send a request again to hold the seats.There is no guarantee of same seat number.
5.	Get notification of expiration of seat hold.
6.	Seat numbers is assigned for the user
7.	User can hold and reserve the seats at multiple levels 

###Building Project
1.	Clone this project :
2.	Git clone 
3.	Kindly make sure JAVA_HOME environment variable is configured and maven bin directory is added to PATH environment variable. Run the following commands
4.	Cd ticket-service
5.	Run command mvn clean install
6.	 Go to target folder by ‘cd target’
7.	 To run  the program use ‘Java -jar ticket-service.jar’ command.

 
