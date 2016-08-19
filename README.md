# spring-boot-starter-mail-sample
A sample spring boot application using spring-boot-starter-mail to send email.

## Steps to run the spring boot application
- mvn clean install
- mvn spring-boot:run

The server is now running on port 8080

## Run dummy SMTP Server locally
I use python for this.

```sudo python -m smtpd -n -c DebuggingServer localhost:25```

## Trigger email
```curl -X POST http://localhost:8080/email/trigger```
