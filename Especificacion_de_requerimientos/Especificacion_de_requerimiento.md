## **INTRODUCCION** 

El presente documento tiene como objetivo brindar una descripción detallada de los requerimientos para el sistema de gestión de requisitos de un punto de ventas y manejo de datos de la información que se le desarrollara a la empresa Variedades Mary, obtenidos en el análisis realizado por parte del equipo de aprendices en conjunto con el cliente.

## **PROPOSITO** 

El propósito de este documento es describir de manera formal el comportamiento del sistema para la implementación de una plataforma WEB que se pretende construir. que tendra capacidad para gestionar, realizar ventas y almacenar la informacion que se trabajara dentro la plataforma realizada para el almacen Variedades Mary. A continuación se detallan los requerimientos funcionales y no funcionales, las restricciones y atributos de calidad que deberá cumplir el sistema. El documento está dirigido a:

1. El cliente.
2. Todos los miembros del equipo de desarrollo aprendiz.
3. El Instructor.


## **ALCANCE**

El alcance de este proyecto será el de crear una plataforma web para el comercio Variedades Mary para que se les facilite en almacenamiento y recolección de información de sus artículos y al igual crearle un punto de ventas en línea y así poder solucionarle la perdida de información que se tiene al realizar las ventas. Gracias a la plataforma web habrá una mejor comunicación de cliente a vendedor. Este software tendrá las siguientes funciones y especificaciones:

1. Tendrá una base de datos con el inventario de los artículos.
2. Tendrá un punto de venta en línea.
3. Habrá un mejor contacto con el cliente comunicación de cliente.
4. Tendrá una sintaxis amigable y fácil de usar.
5. La plataforma tendrá un módulo de registro de actividades y de registro de usuarios.

El proyecto tendrá la duración de año y medio y al terminar el proyecto solo se hará entrega del software ya funcionando al almacén Variedades Mary.

## **DEFINICION,ACRONIMOS,ABREVIATURAS**

1. ADSD-Analisi De Software de Documentacion .
2. BD-Base de datos. 
3. RIP-Registro de Informacion General.
4. CMS-siglas de Content Management System.
5. RPA-Automatización Robótica de Procesos.


##**DEFINICIONES**

**Optimizacion:**

Optimizar quiere decir buscar mejores resultados, más eficacia o mayor eficiencia en el desempeño de alguna tarea. De allí que términos sinónimos sean mejorar, optimar o perfeccionar. 

**Mercantilizar:**

La mercantilización es el proceso de transformación de bienes y servicios en mercancías comercializables con fines de lucro. Es decir que el valor de cambio de los objetos prevalece sobre su valor de uso.

**Regularizacion:**

Regularización es el proceso y la consecuencia de regularizar. Este verbo se refiere a normalizar, ordenar, reglamentar o sistematizar algo.

**Prototipo:**

Primer ejemplar que se fabrica de una figura, un invento u otra cosa, y que sirve de modelo para fabricar otras iguales, o molde original con el que se fabrica.

**Sector terciario:**

El sector servicios o sector terciario es el sector económico que engloba las actividades relacionadas con los servicios no productores o transformadores de bienes materiales. Generan servicios que se ofrecen para satisfacer las necesidades de cualquier población en el mundo.

**La boutique:**

La palabra boutique se refiere, por lo general, a una tienda exclusiva, de ropa o accesorios de moda. ... Así, hoy en día el término boutique también hace referencia a un establecimiento o negocio que comercializa o se especializa en productos o servicios muy selectos o exclusivos.

A lo largo de todo el documento, se utilizan los términos Requisito y Requerimiento en forma distinta.

## **DEFINICION**

En esta definición se planea exponer los datos recopilados por nosotros como grupo de aprendices S.E.N.A hemos recopilado desde el día sábado 9 de mayo del año 2020.

Este proyecto está diseñado para el beneficio y aporte al sector economico en el area textil. La boutique es una de las mas importantes y uno de los grandes establecimientos en el sector donde se encuentra. el cual se caracteriza en la venta de artículos de moda y lujo como prendas de vestir y joyería. reconocido por su gran variedad y calidad de sus productos, ademas de su enorme fiabilidad a la hora de mercantilizar. queriendo lograr una extension en en el area que desempeña llevando esto hasta el domicilio del cliente, a lo que ahora se le conoce como tienda virtual. 

Este proyecto está siendo elaborado con el fin de sistematizar y optimizar la cantidad de informacion que es suministrada a diario. Referente a ventas, compras, stock, observaciones y demas. 

la razón por la que hicimos enfasis en la parte de la obtencion de la informacion y su procesamiento, fue gracias al  estudio y analisis sobre esta. Que puso en descubierto la perdida de informacion, la falta de optimizacion, esfuerzo mental por parte de los empleados encargados y sobre todo la falta de regularizacion y su obtencion de informacion. 

La tienda se encuentra sin automatización para este medio teniendo que recurrir a catalogar la información artesanalmente, esto ha llevado a un gran retroceso para la empresa bajando su productividad. ya hemos sido autorizados por la propietaria del emprendimiento (Maria buelvas) para ayudar a la creación del prototipo del software web para el almacenamiento de información, el cual para habilitar y entregarlo totalmente restan 14 meses de aprendizaje.

## **APRECIACION GLOBAL**

Este documento esta conformado por secciones que son el proposito, el alcance, y la ultima seccion es donde estan las definicines y los pormenores de los requisitos. en esta primera seccion se procura proporcionar una vision general de las funciones que cumplira o no el software. En la segunda seccion se da una descripcion general del sistema a construir, para conocer los datos requeridos y sus funciones generales, aunque no se entra en detalles de cada uno de esto factores. y por ultimo  tambien se conoceran las definiciones y los pormenores del software.

## PERSPECTIVAS DEL SOFTWARE

Las perspectivas de este software son que el la empresa  tendra un facil acceso, control y obtencion de la informacion. sobre ventas,compras,observaciones y demas sobre los clientes y proveedores de la tienda. El sistema funcionará en un ambiente web, por lo que deberá ser capaz de funcionar en cualquier plataforma con un navegador web instalado, siempre
y cuando disponga de conexión al servidor en que va a estar corriendo la aplicación, ya sea por Internet o alguna red privada.

## FUNCIONES DEL SOFTWARE

1. Almacenamiento de infomacion. 
2. Control de la informacion.
3. Facilidad al buscar los datos.
4. Simplicidad de obtencion de la informacion.

## CARACTERISTICAS DE USUARIO

El producto a construir va dirigido a tres tipos de usuarios principales. En
primer lugar, usuarios con conocimientos avanzados en lo referente a
sistemas de información, que poseen conocimientos específicos  En
segundo lugar, está dirigido a clientes de proyectos que en algunos casos
no tienen conocimientos sobre el tema. 

El sistema cuenta con tres tipos de usuario final, los cuales cada uno de ellos puede representar un rol, que incide forma directa o indirecta con la tienda ya sea como: Empleado(cuerpo administrativo), cliente o proveedor.

• El primero se conforma de ; personas con nivel escolar
promedio de preparatoria, deben tener conocimientos básicos de computación
(e.g. ofimática). “Nivel Administrativo", empleado o Personal laboral a disposicion de la administracion.

• El siguiente nivel lo constituyen sobre todo el personal administrativo, el cual incluye
también al personal capacitado a dispocion de estos, como lo puede ser un jefe de empleados ; son personas con niveles de educación superior al menos, con capacidad de manejo intermedio de equipo de cómputo, se
requieren conocimientos mínimos de uso de sistemas ABC. “Nivel Académico”.

• En el nivel restante va referente a los clientes, con al menos uan formacion basica primaria, que tal se encuentran en un desarrollo o etapa de la vida ya sea: adolecencia, juventud, adultez,  y la vejez que tal usuario está pensado que no sea afín a la tecnología y que en un caso extremo no sepa usarla.”personal longevo”.



## RESTRICCIONES



## ATENCION Y DEPENDENCIAS 



## REQUERIMIENTOS FUNCIONALES

A continuación, se detallan los requisitos funcionales que el sistema deberá implementar.

1. Autenticación y autorización de usuarios:
- El sistema deberá permitir a los usuarios iniciar sesión en el mismo. También deberá permitirles cerrar sesión una sesión iniciada previamente
2. Gestión de información
- El sistema deberá permitir que los usuarios modifiquen los datos registrados en la base de datos de la plataforma web como.
3. Consulta de información
4. registro de información
5. Visualizar información
5. Reportes de las ventas
6. Almacenamiento de información 


## REQUERIMIENTOS NO FUNCIONALES

**01-Interfaz del sistema**

La interfaz del sistema debe estar implementada como una aplicación web,
a excepción de la extensión para Smart Devices. Se pretende además la
existencia de un portal de requisitos.

**02 - Usabilidad**

El sistema deberá proveer una interfaz amigable al usuario, que sea fácil
de aprender y de usar. Se pretende que la navegación entre las distintas
funcionalidades del sistema sea realizada en forma sencilla y en pocos
pasos. La interfaz deberá ofrecer funcionalidades para realizar tareas
repetitivas en forma automática.

##**Ejemplo:**

**Inicio de sesión automática en un sitio web:** 

Al automatizar el inicio de sesión y el proceso de navegación de un sitio web se pueden ahorrar muchas horas de procesamiento manual.

**Navegación automática en un sitio web**

**Scraping: extraer datos de una página web de forma automática**

**03 - Utilización de GAM**

Se deberá utilizar Genexus Access Manager para toda la gestión de usuarios
y control de acceso; autenticación y autorización.

**Requerimientos de Interfaz externa**

-Interfaz de usuario.

-Estándar de GUI.

-Distribución de la pantalla.

-Restricciones de resolución.

-Estándares de botones, funciones o enlaces de.

-navegación que aparecen en cada ventana.

-Teclas “shortcut”.

-Estándares de mensajes de error.
