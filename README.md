# QA CHALLENGE

Hola, bienvenido al QA Challenge para el perfil de Analista de Calidad. A continuación encontrarás una serie de retos que deberás realizar.
Recuerda tener en cuenta las consideraciones para poder resolver los retos.

## Consideraciones
* Las respuestas de los retos deberan ser colocados en el documento qa-challenge-[nombre del postulante].docx
* El documento qa-challenge-[nombre del postulante] deberá ser adjuntado como respuesta en el correo que el postulante envie.
* Los retos deberan ser resueltos como máximo en un plazo de 48h.
* Recuerda que estos no son ejercicios de calificación, no hay respuestas válidas o inválidas.

## Reto 1

Se le ha pedido al area de TI desarrollar 2 requerimientos.
* Registro de usuarios
* Login de Usuarios
A continuación se adjunta los mockups de los diseños y la Historia de Usuario.

![registro](/registration.png) 
![login](/login.png)

> ### Historia de Usuario
> Como un nuevo usuario quiero poder registrarme y loguearme para poder navegar dentro de la plataforma
> #### Criterios de Aceptación
> Los criterios de aceptacion para el registro son los sgtes:
> * Los campos First Name, Last Name deben tener como maximo 50 caracteres y como minimo 1 caracter. Son obligatorios.
> * El campo Security Question es obligatorio.
> * El campo Security Aswer es obligatorio y debe tener como maximo 100 caracteres.
> * El campo Username es obligatorio y debe tener como minimo 5 caracteres y como maximo 25. Es un campo tipo email y debe cumplir con el formato de correos.
> * Los campos Password y Confirm Password deben tener al menos 6 caracteres.
> * El sistema debe mostrar un mensaje de error al ingresar campos no válidos.
> 
> Los criterios de aceptacion para el login son los sgtes:
> * El campo user ID es un campo tipo email y debe cumplir con el formato de correos.
> * El password debe tener al menos 6 caracteres.
> * La opción Show Password debe mostrar la contraseña por unos segundos.
> * La opción Keep me sign in debe mantener activa la sessión del usuario.
> * El sistema debe mostrar un mensaje de error al ingresar campos no válidos.

  ### Se Requiere
  * Mencionar que técnica de diseño de casos de prueba usarías para generar los casos de prueba
  * Redactar los casos de pruebas que creas conveniente para los dos requerimientos
  * Listar las mejoras que puedas indentificar para ambos requermientos

## Reto 2

A continuación tienes una base de datos de empleados sus titulos, salarios y departamentos a los que pertenecen. Deberas conectarte a la base de datos con los accesos a continuacion para poder resolver el reto.

> ### Accesos DB
> host: employees.cakjqxz98pwt.us-west-2.rds.amazonaws.com
> 
> user: qa
> 
> password: qachallenge2021$
> 
> port: 3306
> 
> database: employees

  ### Se Requiere
  * Escribir la consulta SQL para listar los 100 primeros empleados(employees table) de genero fememino(gender column) ordenados por numero de empleado (emp_no column) de forma ascendente
  * Escribir la consulta SQL para listar todos salarios(salaries table) del empleado 10001 (emp_no). La consulta SQL debera relacionar las tablas employees y salaries, usando un INNER JOIN.
  * Escribir la consulta SQL para listar los 10 ultimos empleados(employees table) con sus respectivos titulos(titles table). La consulta SQL debera relacionar las tablas employees y titles, usando un INNER JOIN.
  * Escrbir la consulta SQL para listar todos los empleados(employees table) con sus respectivos departamentos(departments table) entre las fechas desde(from_date column, dept_emp table) 1992-12-18 hasta(to_date column, dept_emp table) 1997-10-15. Debera relacionar las 3 sgtes tablas: employees, dept_emp, departments.
  * Escribit la consulta SQL que retorne la cantidad de empleados que existen.
  








