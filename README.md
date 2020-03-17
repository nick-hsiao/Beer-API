# Beer-API
simple rest api using java, springboot and mysql


#Application.properties
application.properties file is not provided because environment variables are not working.
the template is below:

spring.datasource.url=${mysql_url}
spring.datasource.username=${mysql_username}
spring.datasource.password=${mysql_pass}
spring.jpa.hibernate.ddl-auto=update

spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect

Place this file in /src/main/resources and the application should run