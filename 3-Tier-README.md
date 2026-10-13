  3 Tier Architecture

 

Service 	Port	 Technology	Version
Frontend	80	   Nginx + React	nginx 1.26, React 19
Catalogue	8080	 Node.js	24
User	    8080	 Node.js	24
Cart    	8080   Node.js	24
Shipping	8080	 Java (Spring Boot 4)	OpenJDK 25, Maven 3.9
Payment 	8080	 Python (Flask + gunicorn)	3.14
Dispatch   --	   Go (consumer only)	1.25 or newer
MongoDB   27017	 NoSQL Database	7.0
Redis	    6379	 In-memory Cache	7
MySQL	    3306	 SQL Database	8.4
RabbitMQ	5672	 Message Queue	4.x
