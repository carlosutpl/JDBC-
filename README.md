# JDBC
## Segundo trabajo de consulta | Semana 15
------------------------
## ¿Qué es el JDBC? 
El JDBC o Java Data Base Connnectivity es un conjunto de clases programadas en JAVA los cuáles nos permiten trabajar con una base de datos directamente desde código JAVA o algún otro lenguaje de programación que tenga las librerías de JAVA nativas y/o use JVM *(Java Virtual Machine)*.  

En este caso, el lenguaje de Scala al hacer un lenguaje declarativo y funcional nos permite trabajar mucho más comodamente con *JDBC* ya que su sintaxis y sus funcionalidades la hacen una mejor herramienta a la hora de diseñar sistemas de back-end o en el servidor. Sus componentes, tiene varias clases que nos permiten trabajar

## Diferencias entre las librerías de Slick y Doobie en Scala:
![image](https://github.com/user-attachments/assets/a742933b-4d89-48bc-8ed0-d0d230244df4)

## Conexion con MySQL:
He creado la siguiente tabla:
```sql
CREATE TABLE animales (
  id int,
  tipo varchar(255), 
  estado varchar(255),
  PRIMARY KEY (id)
);
```

Contiene los siguientes datos:


![image](https://github.com/user-attachments/assets/32dd945a-c5a8-44ce-b606-354a8a599f39)


