*Al menos 3 casos de uso por requerimiento*
# *Software Requirements Specification*<br>para<br>*Project*
#### Version 1.1 approved
#### Preparado por Bernardo Paniagua, Ricardo Alonso y Ricardo Edward
#### Equipo sin equipo
#### 11/27/20


## **Tabla de Contendios**
[**Tabla de Contendios**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#tabla-de-contendios)

[**Historial de Revisión**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#historial-de-revisi%C3%B3n)
1. [**Introducción**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#1-introducci%C3%B3n)
    1. [Propósito](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#11-prop%C3%B3sito)
    2. [Convenciones del documento](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#12-convenciones-del-documento)
    3. [Audiencia enfocada y sugerencias de lectura](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#13-audiencia-enfocada-y-sugerencias-de-lectura)
    4. [Alcance del producto](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#14-alcance-del-producto)
    5. [Referencias](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#15-referencias)
2. [**Descripción general**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#2-descripci%C3%B3n-general)
    1. [Perspectiva del producto](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#21-perspectiva-del-producto)
    2. [Funciones del producto](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#22-funciones-del-producto)
    3. [Clases de usuario y características](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#23-clases-de-usuario-y-caracter%C3%ADsticas)
    4. [Entorno operativo](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#24-entorno-operativo)
    5. [Restricciones de diseño e implementación](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#25-restricciones-de-dise%C3%B1o-e-implementaci%C3%B3n)
    6. [Documentación de usuario](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#26-documentaci%C3%B3n-de-usuario)
    7. [Suposiciones y dependencias](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#27-suposiciones-y-dependencias)
3. [**Requerimientos de interfaz externa**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#3-requerimientos-de-interfaz-externa)
    1. [Interfaces de usuario](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#31-interfaces-de-usuario)
    2. [Interfaces de hardware](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#32-interfaces-de-hardware)
    3. [Interfaces de software](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#33-interfaces-de-software)
    4. [Interfaces de comunicación](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#34-interfaces-de-comunicaci%C3%B3n)
4. [**Funcionalidades del sistema**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#4-funcionalidades-del-sistema)
    1. [Funcionalidad 1](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#41-el-sistema-utiliza-la-cuenta-del-itam-para-autentificar-a-lxs-usuarixs)
    2. [Funcionalidad 2](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#42-el-sistema-crea-una-sala-por-cada-clase)
    3. [Funcionalidad 3](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#43-lxs-alumnxs-pueden-crear-salas-personalizadas-con-otrxs-alumnxs-yo-profesorxs)
    4.  [Funcionalidad 4](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#44-un-alumnx-puede-solicitar-un-chat-con-el-personal-administrativo)
5. [**Otros requerimientos no funcionales**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#5-otros-requerimientos-no-funcionales)
    1. [Requerimientos de rendimiento](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#51-requerimientos-de-rendimiento)
    2. [Requerimientos de protección](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#52-requerimientos-de-protecci%C3%B3n)
    3. [Requerimientos de seguridad](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#53-requerimientos-de-seguridad)
    4. [Atributos de calidad de software](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#54-atributos-de-calidad-de-software)
    5. [Reglas de Negocio](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#55-reglas-de-negocio)
6. [**Otros requerimientos**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#6-otros-requerimientos)

[**Apéndice A: Glosario**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#ap%C3%A9ndice-a-glosario)

[**Apéndice B: Modelos de análisis**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#ap%C3%A9ndice-b-modelos-de-an%C3%A1lisis)

[**Apéndice C: Lista por determinar**](https://github.com/Ingenieria-de-Software-ITAM-2020/Equipo-sin-equipo-/blob/main/Software%20Requirements.md#ap%C3%A9ndice-c-lista-por-determinar)

## Historial de Revisión

| Nombre | Fecha | Razón del cambio | Versión |
| ------ | ----- | ---------------- | ------- |
|Ricardo Meadowcroft |21/11/2020 |Desarrollo de secciones 1,3, 4 y 5 | 0.1|
| | | | |

## **1. Introducción**
### 1.1. Propósito
El propósito de este documento es describir los requerimientos de software para un sistema de comunicación que sirva a los alumnos, profesores y personal administrativo del Instituto Tecnológico Autónomo de México, que pueda funcionar de manera autónoma basada en el servidor del plantel educativo.

### 1.2. Convenciones del documento
Las funcionalidades están ordenadas de manera general por prioridad.
REQ-X significa requerimiento número X.

### 1.3. Audiencia enfocada y sugerencias de lectura
Este documento sera usado por los desarrolladores de este software para llevar a cabo la programación correcta de las funcionalidades descritas, para esto es importante leer todo el documento. Además, se espera que el personal directivo y administrativo del ITAM, particularmente en el departamiento de ingeniería en computación para avalar que las funcionalidades cumplan con el propósito esperado; para estos es de interés particular el apartado 4 de este documento.

### 1.4. Alcance del producto
Se busca que este software facilite la comunicación entre los distintos integrantes del plantel educativo del ITAM, permitiendo que los alumnos inscritos en esta institución se comuniquen entré sí para facilitar desarrollo de trabajos y estudio, y además permitir a estos entrar en contacto de manera fácil con sus profesores y con el personal administrativo de la universidad.

### 1.5. Referencias
List any other documents or Web addresses to which this SRS refers. These may include user interface style guides, contracts, standards, system requirements specifications, use case documents, or a vision and scope document. Provide enough information so that the reader could access a copy of each reference, including title, author, version number, date, and source or location.

## **2. Descripción general**
### 2.1. Perspectiva del producto
Este sistema debe ser independiente de los otros softwares ya existentes, ya que representa una funcionalidad diferente. Sin embargo, debe utilizarse en un servidor del ITAM, para mayor seguridad.

### 2.2. Funciones del producto
* Los alumnos, profesores y personal administrativo que cuenten con un correo administrativo podrán usar su cuenta para acceder a este servicio y mandar mensajes a otros usuarios del servicio.
* Los usuarios tendrán la capacidad de crear salas con otros usuarios para poder todos mensajear en ella, para, por ejemplo, coordinar el desarrollo de trabajos prácticos asignados por sus clases, o formar grupos de estudio.
* Se creará de manera automática al inicio de cada semestre una sala de chat para cada clase que se tendrá, donde todos los alumnos inscritos podrán mandar mensajes, y que podrá ser administrado por el profesor correpsondiente.
* Se contará con un método sencillo para que los estudiantes puedan pedir ayuda al personal administrativo, asignando personal para mandar mensajes basado en el tipo de apoyo que requiere.

### 2.3. Clases de usuario y características
* La clase de usuario con mayores integrantes es el de los estudiantes del ITAM, que estarán comunicandose principalmente entre sí para coordinar trabajos y grupos de estudio, con sus profesores respectivos en cada clase para enterarse de informacion pertinente a esta, y con el personal administrativo del ITAM para apoyo con inscripciones y trabajo en el plantel de servicio social, entre otros. Estos deben ser alumnos vigentes actuales del plantel con cuenta para poder acceder al servicio. Se espera

* La clase de profesores tendrá capacidades similares a los usuarios, pero contará además con la capacidad de administrar salas de chat creados automáticamente para las clases que imparte cada semestre, para comunicarse con sus alumnos; se espera que el mayor uso de la aplicación por esta clase sea en estas salas, aunque tambien podrá usarlas para mensajear uno a uno con sus alumnos para asuntos menos públicos.

* La clase administrativa podrá usar las funciones del chat para comunicar con los alumnos información importante respecto al proceso educativo, en que podrá ser asignado una sala autómaticamente a los estudiantes que busquen ayuda, facilitada por el software. Además podrán coordinar entre ellos el funcionamiento correcto del plantel, aunque se busca enfatizar la mayor importancia de comunicación relacionado directamente con el proceso educativo de la institución.

* La clase de moderadores es un subconjunto de los administradores que cuentan con un nivel elevado de privilegio en la aplicación; esto se debe a que serán capaces de ver los mensajes en salas de chat en las que no tiene que pedir permiso entrar, de donde requiere entonces ser vetado por el ITAM para usar sus privilegios exclusivamente para hacer valer el código de conducta de la institución en casos que la administración lo solicite.

### 2.4. Entorno operativo
El software operará en los servidores del Instituto Tecnológico Autónomo de México, funcionando como un servicio web que podrá ser accedido por el Internet dentro y fuera del plantel, a través de una mayoría de navegadores web que podrán funcionar en tanto computadoras del plantel y personales como dispositivos móviles.

### 2.5. Restricciones de diseño e implementación
El servicio debe ser capaz de hacer interfaz con el log in de la institución de manera que resguarde seguramente la información de contraseña del usuario, limitando su uso a aquellos que poseen cuenta del ITAM, y el servicio deberá ser capaz de correr de manera autónoma en el hardware que poseen los servidores del plantel.

### 2.6. Documentación de usuario
El servicio contará con una descripción de como se usa alojado en el sitio web del ITAM, además de una descripción de cómo aplica codigo de conducta del plantel para su uso, y los usos permitidos y recomendados del software.

### 2.7. Suposiciones y dependencias
El incio de sesión de este servicio será por medio de la base de datos de alumnos del itam, por lo que para funcionar depende de ella, además solo hará consultas, por lo que no afectará la información de la misma. Además, su principal vía de acceso será por medio de las plataformas de alumnos ya existentes, por lo que también se asume que un link de acceso será agregado a estas y que se informará a los usuarios de su ubicación y culquier modificación que esta pueda recibir.

## **3. Requerimientos de interfaz externa**
### 3.1. Interfaces de usuario
La pantalla inicial será un log-in, para iniciar sesión dentro del el chat, esta interfaz sera sencilla, sólo tendrá dos barras para ingresar texto (usuario y contraseña) y un botón para acceder; en caso de ingresar datos erroneos se le inforamará al usuario. Dentro de la aplicación se contará con un menú donde se listarán los chats en los que se es participante, además de una barra de búsqueda para buscar otros usuarios y algunas opciones de configuración. Finalemente, cada chat constará de una barra de texto para escribir mensaje y un botón de enviar, además de algunas opciones para enviar otro tipo de archivos como imágenes o pdfs. De manera general, cada página tendra una barra superior que informará al usuario dondé se ecneuntra, el logo del itam y un botón para regresar.

### 3.2. Interfaces de hardware
Esta aplicación web deberá ser lo mas universal posible, para permitir su acceso a todos los usuarios del ITAM desde la mayor parte de dispositivos posibles, desde un navegador web, por lo que se debe asegurar que todas las funciones son compatibles con las últimas versiones de la mayoría de los navegadores.

### 3.3. Interfaces de software
La base de datos de los usuarios debe estar conectada al la base de alumnos del ITAM, para usar sus datos para la autenticación de los usuarios, además esta aplicación debe ser accesible desde la página web del ITAM y de sus plataformas para alumnos. Por obvias razones es requerido un dispositivo capaz de
acceder a internet desde un navegador y para que funcione de manera óptima se espera que este este en su última version disponible.

### 3.4. Interfaces de comunicación
Para el uso de este servicio de deberá poseer una cuenta del ITAM, suministrada por el mismo, además de un navegador web, de preferencia en su última versión. Para asegurar la privacidad de la institución y sus miembros, además es necesario que todas las comunicaciones se hagan con un proceso de encriptación de por medio. Debido al alcance del mismo, además se deberá infromar al usuario cuando haya un tráfico mayor al esperado para que este considere que la velocidad de la comunicación se puede ver afectada.

## **4. Funcionalidades del sistema**

### 4.1 Lxs alumnxs pueden crear salas personalizadas con otrxs alumnxs y/o profesorxs

#### 4.1.1 Descripción y prioridad

Cada alumnx puede crear salas personalizadas con otrxs alumnxs y/o profesorxs, para mejorar la comunicación entre equipos, alumnxs y maestrxs. Es la prioridad más alta, ya que es el principal objetivo del sistema.

#### 4.1.2 Secuencias de respuesta

* El alumnx entra a la página principal
* El alumnx tiene la opción de crear una sala nueva
* Al crear la sala, el alumnx tiene un buscador de alumnxs y profesorxs para añadir a su sala
* Se crea la sala y se mandan las invitaciones pertinentes
* Cuando se acepta la invitación, el alumnx o profesxr entra a la sala
* Si la sala permanece inactiva por 6 meses, se borra

#### 4.1.3 Requerimientos

&nbsp; &nbsp; &nbsp; &nbsp; REQ-1: La página principal tiene un botón para crear salas

&nbsp; &nbsp; &nbsp; &nbsp; REQ-2: El sistema tiene un buscador de alumnxs y profesorxs activos

&nbsp; &nbsp; &nbsp; &nbsp; REQ-3: El sistema te informa si fuíste invitado a una sala

&nbsp; &nbsp; &nbsp; &nbsp; REQ-4: El sistema mete a la sala a las personas que acepten la invitación

&nbsp; &nbsp; &nbsp; &nbsp; REQ-5: Las salas tienen un botón para añadir a otrxs miembrxs

&nbsp; &nbsp; &nbsp; &nbsp; REQ-6: El sistema puede borrar salas automáticamente

&nbsp; &nbsp; &nbsp; &nbsp; REQ-7: Un usuario puede salirse de una sala manualmente

&nbsp; &nbsp; &nbsp; &nbsp; REQ-8: El creador de la sala puede borrarla manualmente

### 4.2. El sistema utiliza la cuenta del ITAM para autentificar a lxs usuarixs

#### 4.2.1 Descripción y prioridad

Se utilizará el correo institucional para acceder al software, para que solo los miembros de la comunidad ITAM tengan acceso a éste. Tiene prioridad alta, ya que se debe garantizar la confidencialidad y privacidad de las salas de chat.

#### 4.2.2 Secuencias de respuesta

* Al entrar al sistema, se pide el correo institucional y la contraseña
* Si son correctos, entra a la página principal
* En caso contrario, dar un mensaje de error

#### 4.2.3 Requerimientos

&nbsp; &nbsp; &nbsp; &nbsp; REQ-1: El sistema tiene la base de datos de usuarios del ITAM

&nbsp; &nbsp; &nbsp; &nbsp; REQ-2: El sistema solo permite el acceso con una cuenta ITAM vigente

&nbsp; &nbsp; &nbsp; &nbsp; REQ-3: El sistema notifica al usuario si su cuenta o contraseña son incorrectas

### 4.3 El sistema crea una sala por cada clase

#### 4.3.1 Descripción y prioridad

Al tener las listas definitivas, el sistema crea una sala para cada materia que el alumnx tenga inscrita. Antes de iniciar un nuevo semestre, estos grupos se cierran y se borran del sistema. Es de prioridad media, ya que la principal función es crear salas personalizadas.

#### 4.3.2 Secuencias de respuesta

* El alumnx hace su horario
* Cuando se tienen las listas definitivas, el sistema crea una sala por cada grupo
* El sistema añade a cada sala todxs lxs alumnxs inscritos en ese grupo
* Cuando se entregan calificaciones, el sistema elimina la sala

#### 4.3.3 Requerimientos

&nbsp; &nbsp; &nbsp; &nbsp; REQ-1: El sistema tiene la base de datos de los grupos y lxs alumnxs inscritxs

&nbsp; &nbsp; &nbsp; &nbsp; REQ-2: El sistema sabe cuando estos son definitivos

&nbsp; &nbsp; &nbsp; &nbsp; REQ-3 El sistema puede crear salas automáticamente

&nbsp; &nbsp; &nbsp; &nbsp; REQ-4: El sistema puede borrar salas automáticamente

### 4.4 Un alumnx puede solicitar un chat con el personal administrativo

#### 4.4.1 Descripción y prioridad

En caso de necesitar asistencia personalizada, lxs alumnxs pueden acceder a un menú de asistencia, donde se creará una sala con un miembro del personal administrativo, dependiendo del tipo de asistencia que requiera. Prioridad media

#### 4.4.2 Secuencias de respuesta

* El alumnx selecciona la opción *Asistencia*
* Se accede a una interfaz donde el alumnx selecciona el área que crea conveniente para su problema
* Se crea un chat con un miembro del personal administrativo del área seleccionada anteriormente
* El alumnx termina la sala, misma que permanece suspendida por si necesita darle seguimiento al problema
* La sala se borra tras estar 6 meses inactiva

#### 4.4.3 Requerimientos

&nbsp; &nbsp; &nbsp; &nbsp; REQ-1: La página principal tiene un botón que lleva a la página de asistencia

&nbsp; &nbsp; &nbsp; &nbsp; REQ-2: La página de asistencia tiene un botón por cada área administrativa

&nbsp; &nbsp; &nbsp; &nbsp; REQ-3: Seleccionar un área crea una sala con un miembro del personal administrativo indicado

&nbsp; &nbsp; &nbsp; &nbsp; REQ-4: El miembro del personal administrativo puede crear y redireccionar al alumnx a otra sala

&nbsp; &nbsp; &nbsp; &nbsp; REQ-5: Cuando el alumno da por terminada la sala, esta se suspende

&nbsp; &nbsp; &nbsp; &nbsp; REQ-6: Cuando se supende una sala, se hace una encuesta de calidad del servicio

&nbsp; &nbsp; &nbsp; &nbsp; REQ-7: Si el alumnx lo desea, puede reactivar o eliminar una sala suspendida

&nbsp; &nbsp; &nbsp; &nbsp; REQ-8: Si una sala permanece suspendida por 6 meses, se borra automáticamente

## **5. Otros requerimientos no funcionales**
### 5.1. Requerimientos de rendimiento
El software debe ser capaz de estar funcional y servir a los usuarios de manera contínua durante el transcurso de todo el día, a través del año, con particular importancia mantener disponibilidad durante los horarios de clases, y en temporadas del año correspondientes a los exámenes finales e inscripción. El software debe ser capaz de manejar bajo el peso concurrente de multiples alumnos que usen el servicio, siendo capas de manejar a al menos 3000 usuarios concurrentemente, asegurando así su disponibilidad en los momentos mencionados de alto tráfico, donde un porcentaje considerable de las personas involucradas en el itam pueden requerir comunicarse.

### 5.2. Requerimientos de protección
Para migitar el riesgo de acciones contrarias al reglamento del ITAM llevadas a cabo por los usuarios que facilite el chat, se debe mantener un historial de mensajes de cada chat moderable; además se debe delinear claramente a los alumnos el propósito de uso del servicio, que queda limitado a actividades relacionadas con la educación en la escuela, para así advertir contra usos que pueden implicar un riesgo de privacidad para los usuarios.


### 5.3. Requerimientos de seguridad
Se debe asegurar que el software solo sea utilizable por los alumnos, profesores, y personal administrativo del itam, contando por identificación preexistente que asigna el Instituto Tecnológico Autónomo de México. De este modo, se espera que el software sea capaz de autentificar el usuario con su cuenta correo del ITAM y correo correspondiente de manera segura encriptada. Además, el contenido de los chats deben guardarse de manera segura de manera que solo los usuarios en cada chat o cuentas asignadas con capacidades de moderación puedan ver su contenido, y se debe presentar de manera clara a los usuarios quién es capaz de ver los mensajes que manda.

### 5.4. Atributos de calidad de software
De las caracteristicas de calidad del software, las más relevantes, que afectan de mayor manera a las metas del software, son, en orden decreciente:
* Disponibilidad: Este software debe ser idealmente capaz de ser usado por cualquier usuario en cualquier momento, irrespectivo de dia, hora o nivel de tráfico
* Usabilidad: El software debe ser fácilmente comprehensible para los usuarios, tal que la comunicación entre los usuarios se facilite, con un interfaz que permita crear y entrar a chats de manera sencilla, quedando claro con quien se chatea.
* Portabilidad: El chat debe ser usable desde la mayoría de navegadores web que son usados por los usuarios, y desde una mayoría de los sistemas usados para acceder al chat, ya sean computadoras del plantel, computadoras propias de los usuarios, o dispositivos móbiles intelligentes.
* Mantenibilidad: El software debe ser capaz de soportar a chats por varios años, y mantener funcional y disponibles los mensajes mandados a lo largo del tiempo cuando se actualiza.

### 5.5. Reglas de Negocio
Todos los usuarios, alumnos, profesores y personas administrativas, tienen la capacidad de crear grupos de chat, pero solo los profesores podrán administrar los grupos especiales asignados por el software a cada clase. Los unicos usuarios que podrán acceder a los mensajes de chats en los que no fueron invitados son las cuentas de moderador especialmente avalados por el ITAM para esta función administrativa.

## **6. Otros requerimientos**
El software debe ser capaz de moderarse tal que la actividad llevada a cabo en ella cumpla con los reglamentos del ITAM, particularmente los referentes a código de conducta de los alumnos y sobre acoso, tal que se pueda llevar a cabo acción administrativa si es necesario.

## **Apéndice A: Glosario**
Define all the terms necessary to properly interpret the SRS, including acronyms and abbreviations. You may wish to build a separate glossary that spans multiple projects or the entire organization, and just include terms specific to a single project in each SRS.

## **Apéndice B: Modelos de análisis**
Optionally, include any pertinent analysis models, such as data flow diagrams, class diagrams, state-transition diagrams, or entity-relationship diagrams.

## **Apéndice C: Lista por determinar**
Collect a numbered list of the TBD (to be determined) references that remain in the SRS so they can be tracked to closure.
