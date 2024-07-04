CAMBIOS
El archivo application.properties contiene la configuración de la base de datos que utiliza la aplicación Spring Boot. Al cambiar de H2 a MySQL, es necesario actualizar este archivo para que Spring Boot sepa cómo conectarse a la nueva base de datos.

![image](https://github.com/josueleonn/projecthotel/assets/147575712/cf3b135a-7f37-46a6-a0d0-9d55ae0daa8d)

En el archivo pom.xml se necesita agregar la dependencia del conector de MySQL para que la aplicación pueda comunicarse con la base de datos MySQL.

![image](https://github.com/josueleonn/projecthotel/assets/147575712/9829805a-c9ff-47a1-8583-a59baea7f7ef)

