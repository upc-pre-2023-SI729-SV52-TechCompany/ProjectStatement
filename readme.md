### *STUDENT OUTCOME*

A. Criterio específico 1: Comunica oralmente sus ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerárquicos, en el marco del desarrollo de un proyecto en ingeniería.

>TB1
>> **Sanchez Rios, Jean-Patrick**: Para el presente entregable se realizó el análisis de competidores para ver dilucidar mejor la importancia de nuestro valor agregado.

B. Criterio específico 2: Comunica en forma escrita ideas y/o resultados con objetividad a público de diferentes especialidades y niveles jerarquicos, en el marco del desarrollo de un proyecto en ingeniería.

>TB1
> >**Sanchez Rios, Jean-Patrick**: Realice entrevistas y análisis posteriores para el correcto procesamiento de la información con el fin de utilizarlo para mejorar la experiencia de usuaria de nuestra app

### *1.1.2. Perfiles de integrantes del equipo*

INTEGRANTE 2: Mi nombre es Jean-Patrick Yemsi Sanchez Rios, estudiante de la carrera de Ingeniería de Software en la Universidad Peruana de Ciencias Aplicadas. Poseo conocimientos en C++, SQL, gestión de bases de datos, diseño gráfico y control de calidad. Estoy aprendiendo ahora mismo el uso de git en control de versiones, lenguajes de programación como Python, Javascript y css, y poseo conocimientos sobre marcos de trabajo ágiles.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/57b8038d-da35-4648-92c0-da077429f2b9)


### Registro de entrevistas

> #### **Nombre y apellido:** Alex Ganoza Condori
> #### **Edad:** 34
> #### **Distrito:** Breña
> #### **Segmento:** Transportista
> #### **Resumen:**
>En una conversación con Alex Ganoza Condori, un dedicado padre de familia de 34 años con una década de experiencia en el transporte de mercadería, se revelaron detalles interesantes sobre su vida laboral y sus aspiraciones para el futuro. Alex es propietario de su propio vehículo y su sustento depende de la distancia que recorre para entregar mercancía y la cantidad de trabajos que realiza.
Durante la entrevista, Alex compartió que su experiencia en el transporte ha sido en gran parte sin mayores inconvenientes, ya que suele operar rutas tranquilas y tiene un historial de entregas exitosas. Sin embargo, está decidido a expandir su negocio y aumentar su clientela. Para lograrlo, está considerando utilizar un servicio web que le permita llegar a más clientes y brindarles una mayor sensación de confianza.
Alex ve en la tecnología una oportunidad para crecer en su profesión y facilitar las transacciones con sus clientes. Con la implementación de un servicio web, espera tener acceso a un mercado más amplio y ganar la confianza de aquellos que buscan sus servicios de transporte.
> 
> ![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/8dd8ba0a-94ad-4634-b601-0c931fab0d4b)
> 
# CAPÍTULO V: PRODUCT IMPLEMENTATION, VALIDATION & DEPLOYMENT
## 5.1. Software Configuration Management.
En esta parte del documento, se definirán las normas que asegurarán que mantengamos uniformidad durante todo el ciclo de vida de nuestro producto.
### 5.1.1. Software Development Environment Configuration.

**→Project Management**
Se emplearon programas que posibilitan la comunicación instantánea y la colaboración en tiempo real, lo que permitió un trabajo eficiente. Entre las aplicaciones utilizadas se encuentran los servicios de Google (Drive, Documents y Meet), así como Microsoft Outlook. Además, para llevar un registro de versiones y crear repositorios ordenados, se utilizó GitHub, una plataforma que nos permite registrar de manera organizada cada uno de los cambios (commits) que hicimos y haremos.

**→Product UX/UI Design**
Se utilizaron Miro y UXPressia para llevar a cabo todo lo relacionado con la identificación de los segmentos objetivo y la creación de sus mapas. También se aprovecharon estas herramientas en línea para elaborar los mapas de escenarios "As-Is" y "To-Be". En cuanto a la creación de los bocetos, estructuras de alambre y diagramas de flujo, así como el prototipo de la aplicación web, se optó por Figma.
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/b7326022-8777-4dac-ae13-d11330ed6a69)

**→Software Development**
Para el desarrollo del software del presente proyecto se emplearon las siguientes herramientas:

*Visual Studio Code:*Un editor de código fuente altamente personalizable y ampliamente utilizado para el desarrollo de software.

*HTML:* Lenguaje de marcado utilizado para crear páginas web.

*CSS:*Lenguaje utilizado para dar estilo y diseño a las páginas web creadas con HTML.

*Bootstrap:*Un marco de diseño (framework) de código abierto que facilita la creación de sitios web y aplicaciones web con una apariencia atractiva y responsiva.

*Javascript:* Un lenguaje de programación utilizado para agregar interactividad y dinamismo a las páginas web.

*Git:*Un sistema de control de versiones ampliamente utilizado para rastrear cambios en el código fuente y colaborar en proyectos de desarrollo de software.

**->Software Testing**
Para evaluar nuestro landing page, utilizamos una extensión de Visual Studio Code llamada LiveShare. Esta extensión nos permite establecer un servidor local y, gracias a esto, podemos visualizar instantáneamente los cambios que realizamos en un navegador web, como Chrome o Brave. Además, para llevar a cabo las pruebas de aceptación, optamos por emplear el lenguaje Gherkin y posteriormente subiremos estos resultados al repositorio que mencionaremos más adelante.

**->Software Deployment**
Para publicar nuestra Landing Page, dado que se trata de una página estática con contenido que no requiere cambios frecuentes, hemos aprovechado GitHub Pages, una opción gratuita que nos permite actualizar el contenido cuando lo necesitemos.

**->Software Documentation**
En la documentación del software, al emplear HTML para crear la Landing Page, no es necesario generar diagramas de clases u otros tipos de representaciones gráficas. En su lugar, documentaremos el software mediante comentarios en los archivos HTML, siempre que sea necesario.

### 5.1.2. Source Code Management.

    *Main:*Contiene la version estable del proyecto

*Develop:*Esta compuesto por todos los elementos que se han estado desarrollando, y cuando consideremos que está listo para avanzar al siguiente paso, se fusionará con la rama de lanzamiento (release).

*Release:*Incluye código que será oficialmente publicado y servirá como un paso de precaución antes de avanzar a la rama principal (main).

*Feature:*Cada integrante tendrá su propia rama individual donde cargarán las secciones de código asignadas para la funcionalidad específica. Cada una de estas ramas se integrará con la rama "develop".

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/c5c093b6-467e-4e20-a5b0-a54690fea091)

Con respecto a la convención que tendrán los features branches será la siguiente:

    feature _<nombre -integrante>/<pequeña-descripción>

El nombramiento de los releases se hará teniendo en cuenta el versionamiento semántico 2.0.0 con el cual podremos saber cómo nombrar a nuestras diferentes versiones del proyecto. 

Mayor.Menor.Parche

El último dígito (Parche): se utilizará para indicar que hubo un parche. Solo para indicar que se arreglaron algunos errores mas no hubo cambios grandes.

El segundo dígito (Menor): se cambiará (aumentará) para indicar que se añadieron características al proyecto que son compatibles con la versión pasada. Si este dígito aumenta, el número del parche empezará en 0.

El primer dígito (Mayor): Aumentará cada vez que haya un cambio significativo y además cuando la versión actual no sea compatible con la versión anterior. 

Por último, se hará uso de conventional commits para los textos de mensajes en cada commit que se realice. La estructura es la siguiente: 

    <type>[optional scope]: <description>
    [optional body]
    [optional footer(s)]

Sin embargo, para este trabajo, por lo general se usará la siguiente estructura que es similar a la mostrada anteriormente:

    <type>: <description>



### 5.1.3. Source Code Style Guide & Conventions.

Se planea seguir las pautas y convenciones de codificación establecidas en varios recursos, como el HTML Style Guide and Coding Conventions, el Google HTML/CSS Style Guide, las Convenciones Gherkin para Especificaciones Legibles, la Guía de Estilo de Codificación de Angular, la Guía de Estilo de Codificación de Google para Java, la Guía de Estilo de TypeScript de Google y las características de Spring Boot.

**Principales referencias y convenciones adoptadas o por adoptar en la realización del proyecto:**

*HTML*
Las convenciones en HTML son absolutamente necesarias para lograr obtener un código ordenado y consiste, de este modo se volvería más sencillo de comprender. 

→	Declarar siempre el tipo de documento: Se debe declarar siempre el tipo de documento en la primera línea del código. 

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/369a6eaf-4b95-4b04-97ab-6657e01f113f)


→	Usar nombres de elementos en minúscula: A pesar de que HTML permite mezclar mayúsculas y minúsculas, resulta ser una buena práctica escribir todos los elementos en minúsculas. Debido a que es más sencillo de escribir y es una práctica adoptada por la mayoría de los programadores. 

Correcto : ![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/8c24ee6a-16ca-4079-8818-4898135b10f8)

Incorrecto : ![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/d3cd1dde-e1ce-4dfb-ba75-bb323f56a87b)

 
→	Cerrar todos los elementos HTML: No es necesario cerrar todos los elementos, existen excepciones como el elemento <p>. Sin embargo, al igual que la convención anterior resulta ser una buena práctica realizarlo.  

→	Usar nombre de atributos en minúscula: Al igual que con los elementos HTML también permite mezclar mayúsculas y minúsculas, pero resulta ser una buena práctica escribir todos con minúscula. 

→	Cifrar valores de atributos: Es una buena práctica insertar los valores de los atributos entre comillas. Y es obligatorio si el valor contiene espacios. 

→	Utilizar HTTPS: Para imágenes y otros archivos multimedia, hojas de estilos y scripts, siempre y cuando se pueda usar. 

*CSS*

→	Utilizar nombres de clase significativos, que realmente reflejen el propósito del elemento.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/1fc7295a-d4d8-4886-b354-de01de7d17ea)

→	Utilizar un espacio, después de los dos puntos del nombre de una propiedad. 

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/75d83928-f127-4b14-966e-6ec5475327dd)

 
→	Separar las reglas, mediante una línea en blanco. 

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/9bbd13e6-fd0e-4785-9192-436e1f1a29ee)

*JAVASCRIPT*

→	Utilizar camelCase para la nomenclatura: Es una práctica usada por la mayoría de los programadores en JavaScript.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/5d3049da-8d32-4267-93b0-62923a51af05)

→	Terminar siempre una declaración con punto y coma.

→	Evitar las líneas largas, no deben sobrepasar los 80 caracteres.

→	Para cargar JavaScript en HTML se debe usar una sintaxis sencilla y deben tener la extensión js.

*TYPESCRIPT*

→	Las importaciones del espacio de nombres del módulo son lowerCamelCase mientras que los archivos son snake_case.

    import * as fooBar from './foo_bar';

→	 Las llamadas al constructor deben usar paréntesis, incluso cuando no se pasan argumentos:

    const x = nuevo Foo ; //Incorrecto
    const x = nuevo Foo (); //Correcto
    
→	Utilice siempre const o let para declarar variables. Se usa const de forma predeterminada, a menos que sea necesario reasignar una variable. No usar var.

*JAVA*

→	Los modificadores de clase y miembro, cuando están presentes, aparecen en el orden recomendado por la especificación del lenguaje Java:

    →	public protected private abstract default static final transient volatile synchronized native strictfp

→	Se usa UpperCamelCase para el nombre de las clases.

    ThisIsAnExample
    thisIsNotAnExample

→	Se usa lowerCamelCase para el nombre de los métodos y parámetros.

    thisIsAnExample
    ThisIsNotAnExample

*GHERKIN*

Para los archivos. feature se utilizó el lenguaje Gherkin.

→	Contar con bloques discernibles de Given-When-Then, los cuales terminaran aplicando el And y un espacio, para tener una fácil detección de donde termina y donde comienza un bloque. 

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/d77b48a4-e224-4dfd-a3f3-e9314b76a6d2)

→	Utilizar comillas simples, para poder identificar los parámetros en un paso.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/e09bf117-0132-4768-8620-1524ba77d129)


### 5.1.4. Software Deployment Configuration.


Los pasos para llevar a cabo la implementación de la landing page son los siguientes:

Comenzaremos creando un repositorio en GitHub destinado a almacenar los archivos HTML, CSS y JS necesarios. Cada miembro del equipo trabajará en su propia rama "feature" para desarrollar el código de la página. Una vez finalizada una funcionalidad, se realizará una fusión ("merge") con la rama "develop" para asegurarnos de que la landing page esté siempre actualizada.
Posteriormente, configuraremos GitHub Pages para desplegar la landing page utilizando la rama "develop".
Los pasos para realizar el despliegue en GitHub Pages son los siguientes:

1.Crear un repositorio público en GitHub con un nombre que refleje el propósito del proyecto, como "landing-page".

2.Establecer las ramas necesarias según el flujo de trabajo Gitflow, que incluye "main", "release", "develop", "features" y "hotfix".

3.Navegar a la sección de "Configuración" y seleccionar la pestaña "Pages".

4.En la sección de "Pages", se mostrará la configuración para GitHub Pages.

5.En la opción "Rama" ("Branch"), seleccionar la rama desde la cual se realizará el despliegue de la landing page. En este caso, elegiremos la rama "develop" y dejaremos las demás configuraciones en sus valores por defecto.

6.Se generará un enlace que permitirá acceder a la landing page y verá que cada cambio registrado en la rama "develop" se actualizará automáticamente en unos momentos.

7.Cada miembro del equipo trabajará en sus propias ramas "feature" para desarrollar las funcionalidades.

8.Se realizarán fusiones ("merges") adecuadas entre las ramas "develop" y las ramas "feature" para integrar las funcionalidades.

9.Tras esperar unos minutos, los cambios se reflejarán en el enlace proporcionado por GitHub Pages.

10.Ahora tendremos la landing page completamente desplegada junto con todas las implementaciones correspondientes.

## 5.2. Landing Page, Services & Applications Implementation

En esta parte, detallaremos y demostraremos cómo llevaremos a cabo la implementación, pruebas y despliegue de nuestro landing page, así como de los servicios web y la interfaz de usuario de la aplicación web en cada sprint. En cuanto al primer sprint, es importante mencionar que no tenemos como objetivo la creación de servicios web ni el desarrollo de la interfaz de usuario de la aplicación web. Por lo tanto, nuestra atención se centrará exclusivamente en describir el procedimiento de implementación del landing page.

### 5.2.1. Sprint 1
En el presente apartado se registro el avance del trabajo colaborativo.
#### 5.2.1.1. Sprint Backlog 1.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/2d16cf9d-a99d-4d17-9673-5bb60be054ab)

#### 5.2.1.2. Development Evidence for Sprint Review.

Los logros más destacados en la fase de implementación durante este primer sprint son la creación de la versión inicial de nuestro landing page. Además, hemos completado la elaboración de los wireframes, mock-ups y prototipos de nuestra aplicación web.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/7d1e122b-2f6f-4afa-9677-9c861c57f19f)

#### 5.2.1.3. Testing Suite Evidence for Sprint Review.

En este contexto, hemos llevado a cabo las pruebas de aceptación utilizando el lenguaje Gherkin y las hemos cargado en el repositorio. Cada prueba de aceptación incluye la historia de usuario junto con los criterios de aceptación correspondientes para cada escenario propuesto. También hemos adjuntado capturas de las pruebas de aceptación realizadas y las hemos subido a GitHub.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/ba01f9ff-e056-4b5c-b3db-c9458e10ebb7)

#### 5.2.1.4. Execution Evidence for Sprint Review.

Durante este primer sprint, en términos generales, hemos alcanzado los siguientes hitos:

-Establecimiento de múltiples repositorios en GitHub.
-Elaboración de los bocetos visuales del landing page.
-Realización de la implementación del landing page.
-Despliegue del landing page adaptable en GitHub Pages.
-Diseño de maquetas visuales para las diversas pantallas del prototipo de la aplicación web.

![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/f2869da0-4fba-4103-8493-c094d0221ad4)
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/05e0b0a2-4b7f-4c24-9ffc-2aec3c435d14)
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/bb312fcf-0794-4d47-9043-a0360cf5a6c5)
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/129b3fdd-d52c-494f-8f34-eb1afb61fe7e)

#### 5.2.1.5. Services Documentation Evidence for Sprint Review
Durante este primer sprint, no se ha llevado a cabo ninguna implementación relacionada con algún servicio, por lo tanto, esta sección carece de contenido.
#### 5.2.1.6. Software Deployment Evidence for Sprint Review.

Durante este primer sprint, hemos logrado completar de manera exitosa la creación de los wireframes, mock-ups y prototipo de nuestra aplicación web. Además, hemos llevado a cabo la elaboración y el despliegue de nuestra landing page, que está relacionada con el producto que estamos proponiendo, FastPorte. Para alcanzar este último objetivo, hemos realizado las siguientes acciones:

-	Creación de un repositorio en GitHub con el nombre “landing-page”
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/256ea4f7-9df1-4757-950c-cd3c3a5fdca9)

-	Crear las ramas correspondientes al gitflow 
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/4d816452-5acd-4bad-91d5-73aaf693fbb3)

-	Nos dirigimos a “settings” en el apartado “Pages”
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/a9e60cab-81eb-4bb9-a173-f74d05b5def2)

-	Configuramos de esta manera y le damos en “save”: 
![image](https://github.com/upc-pre-2023-SI729-SV52-TechCompany/ProjectStatement/assets/102174297/c36cf071-b074-45ae-834a-dc9f428101b5)

-	Nos generará un link y con ello ya tendremos desplegada la landing page. Con ese link podremos ver las actualizaciones hechas en la rama develop. 

#### 5.2.1.7. Team Collaboration Insights during Sprint.

Para la creación de nuestro prototipo, hemos empleado la herramienta Figma, que nos ha permitido concretar y visualizar lo que habíamos previsto previamente al elaborar los wireframes y mockups. En cuanto a la elaboración de los wireflows y el user flow, hemos confiado en la herramienta Overflow, tal como se especifica en el enunciado del proyecto, ya que es una herramienta sencilla que nos permite diagramar los flujos de la aplicación web para satisfacer cada objetivo del usuario.

Por otro lado, para desarrollar el landing page, hemos utilizado un repositorio en GitHub. En colaboración con el flujo de trabajo Gitflow, hemos implementado de manera conjunta el desarrollo de nuestro landing page. Esto se refleja en los diversos commits realizados en el repositorio, los cuales pueden observarse en las capturas de pantalla adjuntas.

<imagen>

En lo que respecta a la coordinación dentro del equipo, hemos establecido reuniones regulares para discutir las responsabilidades asignadas y distribuir las tareas correspondientes. Esta práctica nos ha permitido mejorar nuestra comunicación y tener una comprensión clara de las responsabilidades individuales. En lo que concierne al desarrollo del código, hemos adoptado un enfoque de segmentación, de manera que cada miembro del equipo se encarga de una sección específica del landing page. Esto facilita una transición fluida entre las partes, ya que el siguiente miembro en la secuencia puede continuar sin problemas. Por último, hemos fomentado un ambiente en el que compartimos ideas y resolvemos dudas de manera regular, lo que ha contribuido a mantenernos actualizados y en sintonía a lo largo del proceso de trabajo.
