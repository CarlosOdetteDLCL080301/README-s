# CLAF
3
# CLAF 2
4
## Pasos para lograr levantar el Frontend y Backend de la pagina de CLAF
***CLAF*** está conformado por los siguientes repositorios:
* [**DTEC REST**](https://132.247.164.51/dtec/dtec-rest): es del modulo ***DTEC*** (Detección, Tránsito, Estabilización y Copiado de materiales) esta compuesto por servicio ***RESTful*** para obtener y actualizar los datos de la base de datos. Es un modulo "independiente" de ***CLAF*** para contralar en las bovedas construidas ese año conocidas como ***AITEM*** (Área de Ingresos, Tránsito y Estabilización de Materiales), los contenedores de latas de film sin revisión, los cuales son controlados por un codigo de barras (***CB***).
* [**CLAF REST**](https://132.247.164.51/claf/claf-spring-boot): es el backend de la aplicación del ***Control Logistico del Acervo Fílmico*** compuesto por servicios ***RESTful*** para obtener y actualizar los datos de la base de datos.
* [***CLIENTE CLAF***](https://132.247.164.51/claf/cliente_front): Este proyecto es la interfaz de la aplicación del ***Control Logístico del Acervo Fílmico*** que se comunica con los servicios ***RESTful*** para obtener y actualizar los datos de la base de datos.
5
## Requisitos para el proyecto 
### Para la codificación
* [Spring Boot V2.1.5](https://spring.io/projects/spring-boot#overview) - El framework Java utilizado.
* [Spring Tools 4](https://marketplace.visualstudio.com/items?itemName=vmware.vscode-boot-dev-pack)    - Extensión para facilitar el desarrollo con Spring (Se especifica que se utilizó la versión de VS Code). 
* [MySQL 5.7](https://downloads.mysql.com/archives/community/)   - No se detalla una versión en especifica, sin embargo, conversando con M.C Gerardo L.L., me comentó que estaba hecho con la versión 5. 
* [Java JDK 11](https://www.oracle.com/mx/java/technologies/javase/jdk11-archive-downloads.html)    -
### Para ejecutar el programa
s
666666
## Clonar repositorios:
* [**DTEC REST**](https://132.247.164.51/dtec/dtec-rest):
    ~~~
    git clone git@132.247.164.51:dtec/dtec-rest.git
    ~~~
* [**CLAF REST**](https://132.247.164.51/claf/claf-spring-boot):
    ~~~
    git clone git@132.247.164.51:claf/claf-spring-boot.git
    ~~~
* [***CLIENTE CLAF***](https://132.247.164.51/claf/cliente_front):
    ~~~
    git@132.247.164.51:claf/cliente_front.git
    ~~~
agregamos modificación
