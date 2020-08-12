Documentación
https://git-scm.com/book/es/v2

Programa de Descarga
https://git-scm.com/

Plataformas Web 
https://github.com/

https://bitbucket.org/

Instalación de GIT en Local
===============================


1. Descargar el cliente Git
https://git-scm.com/

2. Ejecutar El instalador
Aceptar Licencia

3. Carpata de Instalación
C:\Program Files\Git

4. Componentes Impoirtantes
Git Bash (Interprete de comandos)
Git GUI (Entorno Grafico)

5. Crear un menu Git

6. Seleccionar Editor para trabajar
Vim

7. Ajuste de Ruta
Git en linea de comandos y software de Terceros
(Opcjoin recomenadada)


8. Seguridad
OpenSSL  (Secure Shell Line)
Certificados de Autntificación

9. Configurar las lineas conversación
Primera Opcion (Estilos de Windows - Linux)

10. Editor MinTTY

11. Seleccionar la entrega por defecto
Envio antes de una Fusión


12. Habilitar Sistema de Cache

************************************************

Arrancar con GIT
======================================
Windows
1. Buscar mi editor de linea de comandos
Git Bash

Comandos Basicos
Saber la ruta (carpeta en la que estoy actualmente)
pwd

Listar el contenido del directorio actual
ls

Cambiar de directorio (Ingresar)
cd <nombre_carpeta>

Subir un directorio
cd ..


Crear un acuenta de Repositorio Remoto
======================================
GitHub
https://github.com/

Sign Up (Registrar)
a)Escoger un Nombre de Ususrio disponible
SandyMary

b) Registar un correo electronico
exzsam@hotmail.com

c) Password
 1 Mayuscula
 Minusculas 
 Numero
 PalabraClave

 Ej.
 	Sandy-en-Github-2020

d) Verificar Cuenta


e) Crear cuenta


f) Elegir perfil

g) Verificar correo y confirmar cuenta



Paseo por Github
--------------------
Configurar el perfil

Repositorios
New
	Nombre al repositorio
	Pblico / Privado
	Elegir (README)
	Crear repositorio



-----------------------------------------
Bibicket

https://bitbucket.org/

Get Free
1. Registrar Mi correo
	Registrar Correo gmail
	Nombre Usuario
	Password de Bitbucket

2. Seleccionar cuenta Google - Microsoft - Apple
	Microsoft

3. Autentificar ingresando al correo electronico
	Escribir el correo y contraseña del Correo
	(Siempre y cuando no este abierto el correo seleccionado)

4. Ingresar Nombre de Usuario
	SandyMary

5. Ingresar perfil de experiencia
	


Configurar Perfil
-----------------
En la parte inferior
	Profile	
		Personal Settings


Repositorio de Bitbucket
-------------------------
Create Repository
Project: SECODUVI
Repository: Archivo
 Private

 Create Repository





Trabajo con Repositorios Remotos
======================================
Github
--------------
Ir a repositorio y seleccionar el repositorio a trabajar (Archivo)

Clonar mi repositorio hacia local

Opción <Code>
	Seleccionar Clonar Repositorio
		Hacer click (Boton de copiar URL)
			Ej.
			https://github.com/SandyMary/Archivo.git


Acceso con Git Bash


Ingresar a la carpeta Destino

Si estamos en otra ruta

Queremos trabajar con el usuario actual
Cambiar de directorio de usuario
cd ~ (ALT GR + ~)
pwd
cd Github


Borrar carpeta
rm <nombre_carpeta> <opciones>

ej.
rm Github -Rf
- R Recursivo
- f Aceptar todo (force)



Crear Carpeta
mkdir <nombre_carpeta>
Ej.
	mkdir Github

Accesar a Carpeta
cd <nombre_carpeta>

cd Github

Clonar repositorio
---------------------------

Con la URL del repositorio Remoto
Ej.
	https://github.com/SandyMary/Archivo.git

Opcion A
-----------
Configuración Rapida - Si tienes algo como esto puedes hacer:
Via ssh
	Copiar: 
		git@github.com:SandyMary/Ejemplo.git

HTTP:
	Copiar
		https://github.com/SandyMary/Ejemplo.git		

o Crear un repositorio desde linea de comandos

echo "# Ejemplo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/SandyMary/Ejemplo.git
git push -u origin master


Empujamos los cambios a remoto desde linea de comandos
git remote add origin https://github.com/SandyMary/Ejemplo.git
git push -u origin master


Opcion B
---------
Clonación de un repositorio existente
	https://github.com/SandyMary/Archivo.git

En git Bash ubicarnos en la carpeta destino

cd /c/Users/Klvst3r/Github


Clonar
git clone <URL>
Ej.
git clone https://github.com/SandyMary/Archivo.git

En la ventana de Login
	Colocar credenciales
		UserName:
		Pass:
		
Actualizar el archivo

y prepararlo para Subirlo al repositorio Remoto



Actualizar en remoto
==========================		
Configurar mi usuario y correo
$ git config --global user.name "SandyMary"
$ git config --global user.email exzsam@hotmail.com



Verificar cambios en mi archivo
git status



1. Agregar el archivo (s) Actualizados (Modificados)
git add <nombre_archivo>

Abreviatura si se quiere agregar todo el contenido
Ej.
	10 archivos

	git add .
	. Comodin punto agrega todo el contenido


Verificar antes del commit
git status
	(Verde)

	
2. Enviar a Staging Area (Area de preparación)
git commit -m "<mensaje>"

Ej. 
git commit -m "Actualizacion de README"


3. Enviar al git Directory (Directorio Remoto - Repositorio)
git push <origen> <remoto-rama>

Ej.
git push origin master

https://github.com/SandyMary/Archivo/invitations



Hacer un repositorio Privado a Publico
--------------------------------------------
1. Dentro de mi repositorio
Seleccionar Repositorio (Archivo)

2. Ir a Configuración
	Settings (repositorio)

3. Ir a Danger Zone
	(Inferior)	
		Change repository visibility

		Cambiar Visibiulidad	
			Make Public
				Escriba el Usuario y Repositorio
					SandyMary/Archivo

		Aceptar
			I understand change repository visibility


Trsbajo remoto con Bitbucket
===============================
Infgresar a Bitbucket con el login (Microsoft)			

Ir a repositorios

Clonar mi repositorio hacia local

Voy a obtener la liga de clonacion
Ej.
	git clone https://SandyMary@bitbucket.org/SandyMary/archivo.git 


En git Bash (Terminal)

Posicionar en la carpeta de trabajo local


pwd
cd ..
ls
cd Bitbucket
ls

Directorio de trabajo 
Ej.

/home/klvst3r/Bitbucket


git clone https://SandyMary@bitbucket.org/SandyMary/archivo.git


Cambiar contraseña de usuario en Bitbucket
------
Ir al avatar (Parte inferior izquierda)
	Personal Settings
		Para cambiar Nombre, Pssword Desde 
			Actualizar Atlasian Acoun
				https://id.atlassian.com/manage-profile/profile-and-visibility

En seguridad
	Cambiar Contraseña
		Sandy-2020



Acceso Grupal
Dentro del repositorio (Archivo)
	En el menu lateral ir a 
		Reposito Settings
			Usuario y Acceso Grupal
				Agregarmos la cuenta de correo para relaizar la invitacion
					Agregamos los permisos
						Enviamos Invitación


El usuario aceptara la invitacion desde el correo 
Al aceptar ala inviatación me solicitacita Autentificación

En este caso por medio del correo electronico
ej.
	klvst3r@gmail.com 

Clone el repositorio y en la terminal me autentifico con mi password de la cuenta de Bitbucket <Klvst3r>
Ingresar con password de Bitbucket en local



Agregar contenido al repositorio remoto
-------------------------------------------
En el directorio del repositorio en local

ej.
	/home/klvst3r/Bitbucket/archivo


1. En terinal verificar el estado de los archivos modificados
git status 


2. Agregar al staging area 
	git add <nombre_archivo>

	o 


	git add .

3. Preparar el commit el git directory

	git commit -m "Se agrega configuracion de Bitbucket"	


4. Actualizar el contenido en remoto
	git push origin master




Detallar cambios en un archivo modificados
-------------------------------------------

Commando git diff <archivo>

Ej.
	git diff Config-Bitbucket



Problema de Acceso en Bitbucket
-------------------------

Si tenemos asociado una cuenta de Microsoft - Google o Apple al querer actualizar en una maquina distinata del originen, se generara un conclicto en las sesiones, por lo que debo cambiar la contraseña desde 

Cerramos sesiones
	1. Colocamos el corre electronico
	2. Puksar el boton "Haz olvidado tu contraseña"
	3. Restablecer password
	4. Se generara una solicitud de cambio en el correo.
	5. Cambiar o establecer el nuevo password 
	6. Intenar ingresar nuevamente con la nueva clave.
	

	




