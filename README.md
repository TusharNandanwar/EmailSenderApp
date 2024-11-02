# EmailSender Application
### Overview
The EmailSender Application is a web-based solution designed to facilitate the sending and tracking of emails. The application leverages ReactJS for the frontend, providing a modern, responsive user interface, and Spring Boot for the backend, ensuring robust and scalable server-side operations.

### Demo
https://github.com/Avinash4231/EmailSender-Application-Using-ReactJS-and-SpringBoot/assets/119235391/748e8072-d802-467c-8385-d3190646196b


### Features
Email Composition: Compose and send emails with a user-friendly interface.
Email Tracking: Monitor the status of sent emails.
Responsive Design: Accessible from both desktop and mobile devices.
### Technologies Used
Frontend: ReactJS, HTML, CSS, JavaScript
Backend: Spring Boot, Java
Other Tools: Maven, npm, Axios
### Prerequisites
Node.js
Java 8 or higher
Maven
### Installation
Backend (Spring Boot)

##### Clone the repository:
```
git clone https://github.com/Avinash4231/EmailSender-Application-Using-ReactJS-and-SpringBoot.git
cd EmailSender-Application-Using-ReactJS-and-SpringBoot/EmailSenderApp
```

##### Configure the SMTP Configuration
```
spring.mail.host=smtp.your-email-provider.com
spring.mail.port=587
spring.mail.username=your-email@example.com
spring.mail.password=your-email-password
spring.mail.properties.mail.smtp.auth=true
spring.mail.properties.mail.smtp.starttls.enable=true
spring.mail.properties.mail.smtp.starttls.required=true:
```

Update application.properties with your SMTP Configuration details.

##### Build and run the application:
```
mvn clean install
mvn spring-boot:run
```
### Frontend (ReactJS)
##### Clone the repository:
```
git clone https://github.com/yourusername/EmailSender-Frontend.git
cd EmailSender-Frontend
```

##### Install dependencies:
```
npm install
```

##### Start the React application:
```
npm run dev
```
### Usage
Access the application via your web browser at http://localhost:5173.
Register a new user or login with existing credentials.
Use the interface to compose and send emails.
Track the status of your sent emails through the dashboard.
