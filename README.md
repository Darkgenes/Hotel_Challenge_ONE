<a name = "readme-top"></a>

<!--
This was based in Best-README-Template[https://github.com/othneildrew/Best-README-Template/blob/master/README.md#readme-top], and [https://github.com/abhisheknaiidu/awesome-github-profile-readme/blob/master/README.md] 
-->

<!-- Project Shields -->

<div align = "center">
<!-- Stars -->
<a href = "https://github.com/Darkgenes/encryptor_challenge_1_alura/stargazers"><img src = "https://img.shields.io/github/stars/Darkgenes/encryptor_challenge_1_alura" alt = "Stars Badge"/></a>
<!-- Forks -->
<a href = "https://github.com/Darkgenes/encryptor_challenge_1_alura/network/members"><img src = "https://img.shields.io/github/forks/Darkgenes/encryptor_challenge_1_alura" alt = "Forks Badge"/></a>
<!-- Pull requests -->
<a href = "https://github.com/Darkgenes/encryptor_challenge_1_alura/pulls"><img src = "https://img.shields.io/github/issues-pr/Darkgenes/encryptor_challenge_1_alura" alt = "Pull Requests Badge"/></a>
<!-- Issues -->
<a href = "https://github.com/Darkgenes/encryptor_challenge_1_alura/issues"><img src = "https://img.shields.io/github/issues/Darkgenes/encryptor_challenge_1_alura" alt = "Issues Badge"/></a>
<!-- Contribuitors -->
<a href = "https://github.com/Darkgenes/encryptor_challenge_1_alura/graphs/contributors"><img alt = "GitHub contributors" src = "https://img.shields.io/github/contributors/Darkgenes/encryptor_challenge_1_alura?color=2b9348"></a>
<!-- License -->
<a href = "https://github.com/Darkgenes/encryptor_challenge_1_alura/blob/main/LICENSE.txt"><img src = "https://img.shields.io/badge/License-MIT-yellow.svg" alt = "License Badge"/></a>

</div>  

# =*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*

<h2>Nombre del Proyecto: Desafío_Hotel_Java || Project Name: Hotel_Java_Challenge</h2>
<h4>Versión || Version:</h4>1.0.0
<h4>Fecha || Date:</h4>28/09/2023

# =*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*

<details>
  <summary><b>Tabla de contenidos || Table of contents:</b></summary>
  <ol>
    <li>
      <a href = "#1-introducción--introduction">Introducción || Introduction</a>
    </li>
    <li>
      <a href = "#2-indicaciones-del-curso-one--one-course-indications">Indicaciones del curso ONE || ONE course indications</a>
      <ul>
        <li><a href = "#2-1-requisitos--requirements">Requisitos || Requirements</a></li>
        <li><a href = "#2-2-extras">Extras:</a></li>
      </ul>
    </li>
    <li><a href = "#3-instalación--installation">Instalación || Installation</a></li>
    <li><a href = "#4-uso--usage">Uso || Usage</a></li>
    <li><a href = "#5-características--features">Características || Features</a></li>
    <li><a href = "#6-problemas-conocidos--known-issues">Problemas conocidos || Known Issues</a></li>
    <li><a href = "#7-licencia--license">Licencia || License</a></li>
    <li><a href = "#8-contacto--contact">Contacto || Contact</a></li>
  </ol>
</details>

<p align = "right">(<a href = "#readme-bottom">Go to bottom</a>)</p>

## 1. Introducción || Introduction

Se trata de una aplicación llamada "El Hotel Alura", que pretende hacer uso de los conocimientos adquiridos a lo largo del curso (Java y SQL). En este caso, el reto es simular una interfaz de usuario con las opciones de reserva y observación de reservas de un hotel. Tercer Challenge del grupo 5 de ONE llamado "Sprint 03: Challenge Back End Java - Hotel Alura". || It is an application called "El Hotel Alura", which aims to make use of the knowledge acquired throughout the course (Java and SQL). In this case, the challenge is to simulate a user interface with the options of reservation and observation of reservations in a hotel. Third Challenge of group 5 of ONE called "Sprint 03: Challenge Back End Java - Hotel Alura".

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

## 2. Indicaciones del curso ONE || ONE course indications

Las características que utilizaremos son las siguientes: || The features we shall use are as it follows below:

*Uso de base de datos con SQL y MySQL. || Use of database with SQL and MySQL.
*Uso de lo anterior con JAVA. || Usage of above with JAVA. 

### 2. 1. Requisitos: || Requirements

Aquí los requisitos señalados por el curso: || Here are the course requirements:

*Sistema de autenticación de usuario para que solo usuarios pertenecientes al hotel consigan acceder al sistema. || User authentication system so that only users belonging to the hotel can access the system.

*Permitir crear, editar y eliminar una reserva para los clientes. || Allow to create, edit and delete a reservation for customers.

*Buscar en la base de datos todas las informaciones tanto de los clientes como de las reservas. || Search the database for all customer and reservation information.

*Registrar, editar y eliminar datos de los huéspedes. || Register, edit and delete guest data.

Calcular el valor de la reserva en base a la cantidades de días de la reserva y a una tasa diaria que puede ser asignada por ti y en la moneda local de tu país. Por ejemplo, si tenemos una reserva de 3 días y el valor de nuestra diaria son 20$ debemos multiplicar esos 3 dias por el valor de la diaria, lo que serían 60$, todo esto deberá ser hecho automáticamente y mostrado al usuario antes de guardar la reserva. || Calculate the value of the reservation based on the number of days of the reservation and a daily rate that can be assigned by you and in the local currency of your country. For example, if we have a 3 days reservation and the value of our daily rate is 20$ we must multiply those 3 days by the value of the daily rate, which would be 60$, all this should be done automatically and shown to the user before saving the reservation.

Se necesita de una Base de datos para almacenar todos los datos pedidos anteriormente. || A database is needed to store all the data requested above.

## 3. Extras:

Ahora te preguntarás, ¿Cómo sé que datos debo registrar? Para eso el líder del proyecto puso a disposición un Diagrama de Entidad Relación que usaremos para crear las tablas en nuestra base de Datos y que se muestra a continuación: || Now you may be wondering, how do I know what data to record? For that the project leader made available an Entity Relationship Diagram that we will use to create the tables in our database and it is shown below:

![image](https://github.com/Darkgenes/Hotel_Challenge_ONE/assets/88634132/fb002252-270f-4b10-8ec9-fa43cae68a5b)

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

## 4. Uso || Usage:

Primero debes escoger entre las siguientes opciones: || First you must choose from the following options:

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/ad3c3eca-7cd6-4470-960d-971d5dc81a67)

Puedes seleccionar una de las 3 opciones dando click encima de alguno y dando a "OK". En este caso haremos el ejemplo con longitudes: || You can select one of the 3 options by clicking on one of them and pressing "OK". In this case we will do the example with lengths:

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/2b4d28da-0cec-40b1-ac70-8b5279d1bfd1)

Para este caso seleccionaremos metros como primera opción y después de darle "OK", seleccionamos kilómetros y nuevamente damos en "OK". || For this case we will select meters as the first option and after clicking "OK", we select kilometers and click "OK" again.

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/e5f6dd74-b271-4281-98bc-88e717a5d9cb)

Después, ingresamos un valor y damos "OK". Y siguiente a esto se nos mostrará el resultado: || Then, we enter a value and click "OK". And after that the result will be displayed:

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/f2c8a71d-a5c4-4a13-8998-bbf49092019f)

Cabe aclara que, en caso de no ser un número, se lanzará una exception y se enviará un mensaje al usuario diciendo lo siguiente: || It should be clarified that, in case it is not a number, an exception will be launched and a message will be sent to the user saying the following:

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/36f31bef-fdc7-46f5-8837-99ae0c809886)

Al final del ciclo (sea por un error o un ciclo normal), se le pregunta al usuario si desea seguir haciendo uso del programa o si quiere finalizar: || At the end of the cycle (either an error or a normal cycle), the user is asked if he/she wants to continue using the program or if he/she wants to terminate:

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/ca48f2f0-a439-448b-84e9-461de5df1ca9)

En caso de que el usuario indique "No" el programa lanzará el siguiente mensaje y terminará el programa una vez se de clic en "OK". || In case the user indicates "No" the program will launch the following message and terminate the program once "OK" is clicked.

![image](https://github.com/Darkgenes/Challenge_Conversor_ONE/assets/88634132/e700f561-40b8-4b68-ad6e-df058565d846)

Si el usario eligió la otra opción, el programa vuelve a reiniciarse. || If the user chose the other option, the program restarts again.

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

## 5. Características || Features:

Además de las características que debe poseer esta solución según los requisitos y extras, se añadió dos conversores más; temperatura y longitudes. || In addition to the features that this solution must have according to the requirements and extras, two more converters were added; temperature and lengths.

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

## 6. Limitaciones || Limitations:

Se trata de un desafío básico dentro del programa ONE, por lo que no debería ser usado como un convertidor profesional puesto que este no tiene una amplía variedad de opciones y además no posee una API para acceder a los valores de las divisas "en vivo". || This is a basic challenge within the ONE program, so it should not be used as a professional converter since it does not have a wide variety of options and it does not have an API to access "live" currency values. 

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

## 7. Licencia || License:

En la medida en que la ley lo permite, Darkgenes ha renunciado a todos los derechos de autor y derechos afines o conexos sobre esta obra. || To the extent possible under law, Darkgenes has waived all copyright and related or neighboring rights to this work.

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

## 8. Contacto || Contact:

Para cualquier pregunta, duda o comentario, ponte en contacto con el siguiente canal: || For any questions, doubts or comments, please contact the following channel:
- Correo electrónico || email: cristhiam.060201@gmail.com

<p align = "right">(<a href = "#readme-top">back to top</a>)</p>

<a name = "readme-bottom"></a>
