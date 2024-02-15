# DTEC REST
Back end del módulo ***DTEC*** (Detección, Tránsito, Estabilización y Copiado de materiales) compuesto por servicios ***RESTful*** para obtener y actualizar los datos de la base de datos. Creado en 2019 como módulo "*independiente*" de CLAF (o se intentó hacer como microservicio) para controlar en las bóvedas construidas ese año conocidas como *AITEM* (Área de Ingresos, Tránsito, y Estabilización de Materiales) contenedores (latas) de film sin revisión, por lo cual, se controlan únicamente con su código de barras (CB).

## Comenzando 🚀
El backend de CLAF corre con [Spring Boot](https://start.spring.io/) versión 2.1.5 por lo cual sus dependencias provienen de Maven Repository y están definidas en el archivo [pom.xml](https://132.247.164.51/dtec/dtec-rest/-/blob/master/pom.xml). Estas instrucciones te permitirán obtener una copia del proyecto en tu máquina local para propósitos de desarrollo y pruebas. Ve a la sección Despliegue
para conocer como [desplegar](#deploy) el proyecto.

<a name="Requeriment"></a>
## Requerimentos de software
* [Spring Tools](https://marketplace.visualstudio.com/items?itemName=vmware.vscode-boot-dev-pack) en [Visual Studio Code](https://code.visualstudio.com/download)
* [Java JDK 11](https://www.oracle.com/mx/java/technologies/javase/jdk11-archive-downloads.html) (Java Development Kit)
* [Git](https://git-scm.com/downloads)
* [Maven](https://maven.apache.org/download.cgi)
* [MySQL 5.7](https://dev.mysql.com/downloads/windows/installer/5.7.html)

## Consideraciones importantes para la ejecución del software
* Tener previamente instalado todos los programas necesarios mencionados en "[Requerimentos de software](#Requeriment)"
* Tener la base de datos **DGAC** con la estructura correcta
* Revisar las siguientes variables antes de realizar el *build*, en el archivo *application.properties* (ubicado en la ruta "*./src/resources/application.properties*"):
    * La variable "*spring.profiles.active*" se sea igual a *dev*
    * La varibale "*ruta.storage* sea diferente a "*smb://192.168.10.2/VMWARE/CLAF*".

## Propuestas de mejoras a futuro
* La configuración del ambiente debe mejorarse, ya que estas 2 variables deben cambiarse antes de hacer el [build](#build) para [Despliegue](#deploy) en producción.

<a name="build"></a>

<a name="deploy"></a>