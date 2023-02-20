# TutorialGitCommand
 A continuación, te proporciono una guía detallada paso a paso de cómo crear una cuenta en GitHub.

1- Abre la página de inicio de GitHub: Ingresa a la página web de GitHub (https://github.com/) desde tu navegador web preferido.

2- Inicia el proceso de registro: Haz clic en el botón "Sign up" que se encuentra en la esquina superior derecha de la página.

3- Ingresa tus datos: En la siguiente página, deberás ingresar tus datos personales, incluyendo tu dirección de correo electrónico, nombre de usuario y contraseña.


4- Completa el proceso de verificación: Después de ingresar tus datos, se te pedirá que completes un proceso de verificación para asegurarte de que no eres un robot. Selecciona la opción que corresponde a la imagen que se muestra.


5- Selecciona tus preferencias: En la siguiente página, se te preguntará acerca de tus preferencias y experiencia en programación. Puedes seleccionar las opciones que mejor se adapten a ti.


6-Selecciona un plan: A continuación, deberás seleccionar un plan para tu cuenta. GitHub ofrece diferentes opciones, desde planes gratuitos hasta planes empresariales de pago. Selecciona la opción que más se adapte a tus necesidades.

7- Completa la encuesta opcional: Si deseas, puedes completar una encuesta opcional para compartir más información sobre ti. De lo contrario, puedes omitir esta parte y hacer clic en el botón "Submit".

8- Confirma tu dirección de correo electrónico: Después de completar el registro, se te enviará un correo electrónico de confirmación. Haz clic en el enlace de confirmación en el correo electrónico para activar tu cuenta.
¡Listo! Ahora tienes una cuenta en GitHub y puedes comenzar a utilizar sus funciones y herramientas.

CREAR UN REPOSITORIO EN GITHUB

1- Inicia sesión en tu cuenta de GitHub: Abre el sitio web de GitHub (https://github.com) y, si aún no has iniciado sesión, ingresa tus credenciales de inicio de sesión para acceder a tu cuenta.

2- Haz clic en el botón "+": En la esquina superior derecha de la página, haz clic en el botón verde "+". Se desplegará un menú con varias opciones, incluyendo "New repository".

3- Crea un nuevo repositorio: Haz clic en "New repository" para comenzar a crear un nuevo repositorio.
Nueva opción de repositorio en GitHub

4- Ingresa los detalles del repositorio: Se te redirigirá a la página de creación de un nuevo repositorio. Asegúrate de completar los siguientes campos:

Nombre del repositorio: Ingresa un nombre para tu repositorio. Este nombre será visible para los demás usuarios en GitHub.

Descripción: Agrega una breve descripción de tu proyecto o repositorio.

Público o privado: Selecciona si deseas que tu repositorio sea público (visible para cualquier usuario) o privado (visible solo para los colaboradores que agregues).

Inicializar con un archivo README: Si seleccionas esta opción, se creará un archivo README.md vacío en el repositorio.

.gitignore: Si deseas, puedes seleccionar una plantilla de .gitignore que se ajuste a tu proyecto. Esto ayudará a ignorar ciertos archivos o directorios en los commits.

Licencia: Si deseas, puedes seleccionar una licencia para tu proyecto.

5- Crea el repositorio: Una vez que hayas ingresado todos los detalles del repositorio, haz clic en el botón "Create repository" en la parte inferior de la página para crear el repositorio.
¡Listo! Ahora has creado un nuevo repositorio en GitHub. Puedes agregar archivos, ramas y colaboradores al repositorio según sea necesario.

INSTALACIÓN DE GIT EN WINDOWS

Aquí te dejo una guía paso a paso para instalar Git en Windows siguiendo los pasos del instalador:

1- Ve al sitio web oficial de Git (https://git-scm.com/) y haz clic en el botón "Download for Windows".

2-Se descargará un archivo ejecutable en tu computadora. Haz doble clic en el archivo para ejecutarlo. Aparecerá una ventana de instalación con el título "Git Setup".

3- Haz clic en "Next" para continuar con la instalación.

4- Selecciona la ubicación donde deseas instalar Git en tu computadora. La ubicación predeterminada suele ser la adecuada, pero puedes elegir otra si lo deseas.

5- Selecciona las opciones adicionales que deseas instalar, es recomendable seleccionar todas las opciones disponibles durante la instalación, ya que permiten agregar Git a la consola del sistema (CMD), crear accesos directos en el menú Inicio y en el menú contextual del botón derecho del mouse en las carpetas, y generar la consola de Git Bash, una herramienta valiosa para trabajar con Git. Git Bash es una consola de comandos propia de Git que se puede utilizar para realizar tareas de Git de manera efectiva.

6- Es importante no hacer cambios en ninguna opción y no seleccionar ninguna de las configuraciones que se muestran en los siguientes pasos, ya que estas opciones adicionales pueden causar errores que requerirán soluciones adicionales. Por esta razón, en todas las ventanas a partir de ahora, es recomendable hacer clic solamente en el botón "Next".

7- Selecciona el emulador de terminal que deseas usar con Git. Si no tienes preferencia, deja la opción predeterminada.

8- Selecciona el tipo de línea de comando que deseas usar con Git. La opción predeterminada es probablemente la adecuada, pero si estás acostumbrado a otro tipo de línea de comando, puedes seleccionarlo aquí.

9- Es muy relevante elegir la opción "main" en esta sección, ya que se generará el repositorio local sobre esta rama en lugar de la rama "master" que ya no se utiliza. Es importante tener en cuenta esta opción para evitar cualquier confusión en el futuro.
![image](https://user-images.githubusercontent.com/32584525/220130583-f7a9bc34-8ee0-4cb6-aec1-1221eff01bb8.png)

10- Selecciona la opción "Use Git from Git Bash only" si no estás familiarizado con el uso de Git en la línea de comandos de Windows.

11- Selecciona la opción "Enable file system caching" para mejorar el rendimiento de Git.

12- Haz clic en "Next" para continuar.

13-Selecciona la opción "Use the OpenSSL library" y haz clic en "Next".

14- Selecciona la opción "Checkout Windows-style, commit Unix-style line endings" y haz clic en "Next".

15- Selecciona la opción "Use Windows' default console window" y haz clic en "Next".

16- Haz clic en "Install" para comenzar la instalación de Git.

17- Espera a que se complete la instalación de Git. Puede tardar unos minutos.

18- Haz clic en "Finish" para cerrar la ventana de instalación.

¡Listo! Ahora tienes Git instalado en tu computadora con Windows y puedes comenzar a usarlo para manejar tus repositorios.

CONFIGURACION DE SSH 
A continuación, realizaremos algunas configuraciones globales en la instalación de GIT en nuestro equipo. Para hacerlo, abriremos la consola de Git Bash en Windows o la Terminal de Linux.
1- Antes de comenzar a trabajar con Git y GitHub, es necesario configurar nuestro nombre de usuario y correo en Git. Para hacer esto, usaremos los siguientes comandos en la consola de Git Bash o la Terminal de Linux. Es importante asegurarse de que el nombre de usuario y el correo coincidan exactamente con los que se crearon en la cuenta de GitHub, incluyendo mayúsculas y minúsculas si se usaron:
git config --global user.name "TuNombreDeUsuarioDeGitHub"
git config --global user.email "TuCorreo@correo.com"
Reemplaza "TuNombreDeUsuarioDeGitHub" y "TuCorreo@correo.com" con tu nombre de usuario y correo electrónico de GitHub.
2-Después de haber configurado nuestro nombre de usuario y correo electrónico en Git, podemos verificar que las configuraciones hayan quedado correctamente establecidas en nuestro sistema operativo utilizando el siguiente comando en la consola de Git Bash o la Terminal de Linux:
git config --list
Este comando nos mostrará una lista de las configuraciones de Git en nuestro sistema operativo. Verifica que las opciones "user.name" y "user.email" aparezcan en la lista y que los valores correspondan a los que configuraste previamente. Si todo está en orden, podrás empezar a trabajar con Git y GitHub.
3- Si cometiste un error al configurar el correo o el nombre de usuario en Git, puedes corregirlo utilizando el siguiente comando en la consola de Git Bash o la Terminal de Linux: 
git config --global --unset-all user.email
Este comando eliminará cualquier configuración previa del correo que hayas establecido. Para corregirlo, deberás ejecutar nuevamente el siguiente comando con el correo correcto:
git config --global user.email "SuCorreo@correo.com"
Si también necesitas corregir el nombre de usuario, deberás utilizar el siguiente comando:
git config --global --unset-all user.name
Este comando eliminará cualquier configuración previa del nombre de usuario que hayas establecido. Para corregirlo, deberás ejecutar nuevamente el siguiente comando con el nombre de usuario correcto:
Recuerda reemplazar "SuCorreo@correo.com" y "SuUsuarioDeGitHub" con el correo y nombre de usuario correctos que hayas utilizado al crear tu cuenta de GitHub.
4- Con el comando "git config --global init.defaultBranch main" estamos configurando Git para que use "main" como rama por defecto en lugar de "master". De esta manera, cuando creemos un nuevo repositorio, se creará en la rama "main" en lugar de en "master", como solía ser antes.
5- Para realizar la configuración SSH en GitHub, debemos generar una clave SSH que permita la comunicación entre GIT local y GitHub. Para ello, abrimos la consola de Git Bash en Windows o la Terminal en Linux y ejecutamos el siguiente comando:

ssh-keygen

Este comando nos pedirá que confirmemos la ruta donde se creará la carpeta ssh para guardar las claves. A continuación, se nos pedirá que generemos una frase de seguridad, que podemos dejar en blanco si así lo deseamos. Por último, se nos pedirá que confirmemos la clave que hemos generado para acceder a las claves, la cual también podemos dejar en blanco.

Es importante tener en cuenta que después de ejecutar el comando ssh-keygen, debemos dar ENTER tres veces para confirmar las opciones por defecto. De esta forma, se generará la clave SSH necesaria para la comunicación entre GIT y GitHub.
6- El comando "cat ~/.ssh/id_rsa.pub" nos permite mostrar la clave pública generada. Al ejecutar este comando y presionar ENTER, se mostrará la clave en la pantalla de la consola. Esta clave es la que vamos a agregar a nuestra cuenta de GitHub para que pueda reconocer nuestro equipo como un dispositivo autorizado a trabajar con nuestros repositorios.
Luego de generarla la copiamos sin espacios vacíos, ya que vamos a tener que pegarla en GITHUB.
![image](https://user-images.githubusercontent.com/32584525/220136869-df5c7a5c-7d31-4272-a7a4-ff0f93395ac3.png)

7- Para pegar la clave SSH generada en GitHub, debemos seguir los siguientes pasos:
Acceder a nuestra cuenta de GitHub y dirigirnos a nuestro perfil.
Hacer clic en la pestaña "Settings" en la esquina superior derecha.
Seleccionar "SSH and GPG keys" en el menú de la izquierda.
Hacer clic en el botón "New SSH key" en la esquina superior derecha.
En la sección "Key", copiar y pegar la clave generada en el paso 6.
Escribir un título descriptivo en la sección "Title" para identificar esta clave en el futuro.
Hacer clic en el botón "Add SSH key" para guardar la clave en GitHub.
Y estos fueron los pasos para configurar el github ya solo hace falta que subas los proyectos
