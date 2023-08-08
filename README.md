# DBP-SocialNetwork
# PROYECTO FINAL

##### EQUIPO DE DESARROLLO
- Juan Carlos Postigo Cabana
- Aquino Mamani Ana Karina
- Soto Huerta Angela Shirleth
- Colque Noa Valery Andrea

### INTRODUCCIÓN
Nuestro proyecto final es una **Red Social** que fue diseñada con el objetivo de consolidar los conceptos reacionados con el curso **Desarrollo Basado En Plataformas**.  Somos un grupo conformado por cinco estudiantes de la carrera Ciencia de la Computación.
La **Red Social** fue creada con el objetivo de facilitar la publicación de articulos relacionados con nuestra carrera, con el fin de promover la
investigación y servir como red de información privada para los alumnos de Ciencia de la Computación.

### ESTRUCTURA DEL PROYECTO

Nos basamos en el estilo de arquitectura de software Model-View-Controller (MVC), utilizamos tecnologías como ReactJS, NodeJS y MongoDB para las partes del Frontend, Banckend y Base de Datos  respectivamente.

### TECNOLOGÍAS
Las tecnologías utilizadas son las que componen el stack [MERN](https://openwebinars.net/blog/mern-stack-que-es-y-que-ventajas-ofrece/) como MongoDB, Express, ReactJS y NodeJS. 
#### MVC
Model/View/Controller es un patrón de diseño de software predecible que se puede usar en muchos marcos con muchos lenguajes de programación, comúnmente Python, Ruby, PHP, JavaScript y más. Se utiliza popularmente para diseñar aplicaciones web y aplicaciones móviles.

Los componentes de la arquitectura del patrón MVC están diseñados para manejar diferentes aspectos de una aplicación en desarrollo. El patrón de diseño MVC sirve para separar la capa de presentación de la lógica empresarial.
###### Ventajas
- Elimina dependencias innecesarias
- Reutilizable sin modificación
- MVC hace que las clases de modelos sean reutilizables sin modificaciones
- Reutilización de código
- Código extensible
- Alta cohesión
- Más fácil de mantener o modificar
- Soporta múltiples vistas
- Cada parte se puede probar de forma independiente (modelo, vista, controlador) 

#### REACTJS
ReactJS está orientado al desarrollo del cliente, por lo que no es un Framework al uso como pueden ser AngularJS o Knockout, que son un ¨todo incluido¨.
ReactJS se centra en el desarrollo de la Vista. Por esto, es muy común verlo relacionado con otras librerías formando tándem para cumplimentar el desarrollo del resto de la aplicación, como en nuestro caso ReactJS + NodeJS.
###### - Declarativo
React hace que sea sencillo crear interfaces de usuario interactivas. Diseñe vistas simples para cada estado en su aplicación, y React actualizará y renderizará de manera eficiente los componentes correctos cuando cambien sus datos.
###### - Basado en Componentes
Cree componentes encapsulados que gestionen su propio estado y luego compóngalos para crear interfaces de usuario complejas.
Dado que la lógica de los componentes está escrita en JavaScript en lugar de en plantillas, puede pasar fácilmente datos enriquecidos a través de su aplicación y mantener el estado fuera del DOM. 
###### Dependencias Frontend
| Dependencia  | Versión  | Utilidad |
| :--------------- |:---------------:| :-----:|
|   `bootstrap`    | 5.0.1 | Diseño |
|`dotenv`    |    9.0.2    | Variables de Entorno  |
| `reactstrap` | 1.1.2     |   Diseño  |
| `react-router-dom` |  5.2.0     |  Enrutamiento  |
| `web-vitals`  |  8.9.0    | Experiencia Usuario |

#### NODEJS
Node.js es un entorno de ejecución de JavaScript, una plataforma para ejecutar códigos JavaScript en el lado del servidor y hacerlo portátil. En términos sencillos, un entorno de ejecución es donde los desarrolladores ejecutan un programa. Node.js ofrece comodidad para los desarrolladores y además posee muchas herramientas que facilitan el desarrollo a las cuales llamaremos Dependencias y son nombradas a continuación. 
###### Dependencias Backend
| Dependencia  | Versión  | Utilidad |
| :--------------- |:---------------:| :-----:|
|   `body-parser`    | 1.19.0 | Compatibilidad |
|`cors`    |    2.8.5    |  Compatibilidad  |
| `dotenv` |  9.0.2      |  Variables de Entorno |
| `express` |  4.17.1      |  Servidor  |
| `formidable`  |  1.2.2    |  Tratamiento de Datos  |
| `jsonwebtoken` |    8.5.1    |  Seguridad |
| `mongoose` |   5.12.9     |  Base de Datos  |
| `morgan` |   1.10.0     |  Desarrollo |
| `nodemon` |   2.0.7     |  Desarrollo  |
| `uuid` |    3.4.0    |  Seguridad  |

#### MONGODB
MongoDB es una base de datos documental, lo que significa que almacena datos en forma de documentos tipo JSON. Creemos que esta es la forma más natural de concebir los datos; frente al tradicional modelo de filas y columnas, esta es mucho más expresiva y potente.
Lenguaje de consulta rico y expresivo que permite filtrar y ordenar por cualquier campo, independientemente de cómo esté incrustado en un documento.
Admite agregaciones y otros casos de uso modernos, como búsqueda de gráficos o texto, y búsqueda basada en información geoespacial.
Las propias consultas son también JSON, por lo que se programan fácilmente. Olvídese de concatenar cadenas para generar consultas SQL de forma dinámica.
### MANUAL DE USUARIO
#### REQUERIMIENTOS

- [Node.js](https://nodejs.org/en/) 14+
- [MongoDB](https://www.mongodb.com/) 4+
#### INSTALACIÓN
 Clone este repositorio con la linea de comando o descargue y descomprima la carpeta zip con el código del repositorio.
```shell 
git clone https://github.com/Ana-AM/SocialNetwork.git
```
#### Inicialización Backend
- Abrir una consola cmd en la carpeta base del proyecto.
- Ejecute las lineas de comando
```shell 
cd Backend
```
```shell 
npm install
```
- Una vez las depencias terminen de instalarse, puede correr el backend.
```shell 
npm run dev
```
- El resultado deberia ser un mensaje confirmando la conección de a la base de datos.
![](https://github.com/JPostigo48/DBP-B-Social-Network-EPCC/blob/main/Presentacion/DBok.png?raw=true)
>Success.

#### Inicialización Frontend
- Abrir una consola cmd en la carpeta base del proyecto.
- Ejecute las lineas de comando
```shell 
cd Frontend
```
```shell 
npm install
```
- Una vez las depencias terminen de instalarse, puede correr el frontend.
```shell 
npm run start
```
- Automaticamente se abrira en su navegador la pagina de inicio de la pagina web. `http://localhost:3000`

![](https://github.com/JPostigo48/DBP-B-Social-Network-EPCC/blob/main/Presentacion/home.png?raw=true)
>Success.
