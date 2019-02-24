dependencies : 
      
          jpa , mysql

application.properties


          ## Spring DATASOURCE (DataSourceAutoConfiguration & DataSourceProperties)
          ## create database users_database
          ##create database users_database;
          ## use users_database;

          spring.datasource.url = jdbc:mysql://localhost:3306/users_database?useSSL=false
          spring.datasource.username = root
          spring.datasource.password = root


          ## Hibernate Properties
          # The SQL dialect makes Hibernate generate better SQL for the chosen database
          spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect

          # Hibernate ddl auto (create, create-drop, validate, update)
          spring.jpa.hibernate.ddl-auto = update


source : 
            https://www.javaguides.net/2018/09/spring-boot-2-hibernate-5-mysql-crud-rest-api-tutorial.html