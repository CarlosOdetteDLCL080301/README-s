# CLAF
## Pasos para lograr levantar el Frontend y Backend de la pagina de CLAF
***CLAF*** está conformado por los siguientes repositorios:
* [**DTEC REST**](https://132.247.164.51/dtec/dtec-rest): es del modulo ***DTEC*** (Detección, Tránsito, Estabilización y Copiado de materiales) esta compuesto por servicio ***RESTful*** para obtener y actualizar los datos de la base de datos. Es un modulo "independiente" de ***CLAF*** para contralar en las bovedas construidas ese año conocidas como ***AITEM*** (Área de Ingresos, Tránsito y Estabilización de Materiales), los contenedores de latas de film sin revisión, los cuales son controlados por un codigo de barras (***CB***).
* [**CLAF REST**](https://132.247.164.51/claf/claf-spring-boot): es el backend de la aplicación del ***Control Logistico del Acervo Fílmico*** compuesto por servicios ***RESTful*** para obtener y actualizar los datos de la base de datos.
* [***CLIENTE CLAF***](https://132.247.164.51/claf/cliente_front): Este proyecto es la interfaz de la aplicación del ***Control Logístico del Acervo Fílmico*** que se comunica con los servicios ***RESTful*** para obtener y actualizar los datos de la base de datos.

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
