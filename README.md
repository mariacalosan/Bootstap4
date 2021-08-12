`Curso de Bootstrap`

**_He realizado este archivo con la intención de guardar todo lo aprendido en el curso explicando detallada mente los  conceptos  acerca de Bootstrap y por si alguna persona le interesa y le es útil_**

# Modulo 1 del curso de Bootstrap

en el módulo 1 se habla de la introducción que es Bootstrap, que es un framework y como se puede hacer la instalación de Bootstrap

### **¿Qué es Bootstrap?**

Bootstrap es un  framework que trae código **CSS, JS** que fácilmente nosotros podemos utilizar y ajustar a nuestro gusto

### **¿Qué es un framework?**

Un framework es un conjunto de herramientas que le permiten al desarrollador, desarrollar de una manera más sencilla
existen muchos framework, pero en este caso nos estamos enfocando en un framework web

### _Descarga he instalación de Bootstrap4_

### **Pasos**

1. Crea una carpeta en tu escritorio le pondrás el nombre que quieras, la idea de esta carpeta es alojar todo lo que necesitaremos para ir avanzando

2. Dentro del editor que manejes, en este caso yo utilizo el de visual studio code si no lo tienes, acá te dejo un link donde lo puede descargar https://code.visualstudio.com/download, dentro de la carpeta crea un archivo HTML y tres capetas más cada una con un nombre diferente **CSS, JS e IMG**

3. Para la instalación de Bootstrap https://getbootstrap.com/docs/5.1/getting-started/download/ 
   y en la opción de download vamos a dar clic y nos sale toda la documentación para la descarga y descargamos la versión compilada de  Bootstrap

4. Ya después de haber descargado la versión compilada de Bootstrap 
   lo que hacemos es abrir la carpeta que descargamos y vemos que trae dos carpetas que sería la de **CSS y JS**

5. Al abrir ambas carpetas **CSS y JS** vemos que traen varios archivos
   te puedes quedar con todos o con los que elijas, pero yo me quede con el archivo Bootstrap.min.css lo mismo que con el de Bootstrap.min.js estos dos archivos son minificados para que esta ocupe menos espacio en el disco y estos archivos los vamos a apegar en las carpetas que creamos de **CSS y JS** claro está el de  **CSS con el de CSS y el de JS con el de JS**

### **Descarga del jQuery**

por si se preguntan que es jQuery (este es plugin de JS del cual Bootstrap depende)
Para descargar jQuery vamos a ir a este link https://jquery.com/download/ para descarga lo descargamos la versión comprimida él te va a arrojar todo el código lo copias y lo pegas en un archivo que vas a crear llamado jquery.js que va a estar dentro de la carpeta de **JS**

### **Descarga del Popper**

para el Popper es lo mismo que hicimos con el de jQuery lo descargas copias lo que te descargo y lo pegas en el archivo que vas a crear de popper.js para la descarga entras a este link https://popper.js.org/ de este también descarga la versión comprimida

# Vinculación de Bootstrap, jQuery y Popper

Esta es la estructura básica de tu archivo HTML

```html
<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
  </head>
  <body></body>
</html>
```

Dentro de el `Head` vamos a vincular a  bootstrapmin.css que descargamos lo vinculamos
`<link rel="stylesheet" href="css/bootstrap.min.css"/>`

```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="css/bootstrap.min.css" />
  <title>Document</title>
</head>
```

Para vincular los **JS** lo hacemos en él `body` en las últimas líneas es importante que antes de vincular a Bootstrap vinculemos primero lo que es el jQuery y el Popper
` <script src="js/jquery.js"></script>`

` <script src="js/popper.js"></script>`

` <script src="js/bootstrap.min.js"></script>`

````html
<body>
  <script src="js/jquery.js"></script>
  ```
  <script src="js/popper.js"></script>
  ```
  <script src="js/bootstrap.min.js"></script>
  ```
</body>
````

_Ya teniendo lista la instalación de Bootstrap y todo lo demás vamos a seguir con el módulo 2_

# Modulo 2 layouts de Bootstrap

_En mi archivo index podrán ver más detalladamente la implementación de lo que voy haciendo medida de que avanzó en el curso_

Antes de seguir con el módulo 2 en el `Head` donde vinculamos el archivo de Bootstrap vamos a vincular un archivo nuevo que vamos a hacer de **CSS**
`<link rel="stylesheet" href="css/stely.css" />` ese archivo que acabamos de crear es por si acaso queremos escribir nuestro propio codigo css

```html
<head>
  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <link rel="stylesheet" href="css/bootstrap.min.css" />
  <link rel="stylesheet" href="css/stely.css" />
  <title>Document</title>
</head>
```

### **Aprendiendo a usar contenedores**

en bootstra se manejan dos clases, esta la `class="container"` y la `class="container-fluid"`

## container

esta clase centra el contendio manteniendolo con un margen derecho y uno izquiero que hace que se vea centradon este ira cambiando dependien el tamaño de la pantalla manteniendose responsive

`Ejemplo codigo`

```html
<body>
  <div class="container">
    <h1>Tyrone</h1>
  </div>
  <script src="js/jquery.js"></script>

  <script src="js/popper.js"></script>

  <script src="js/bootstrap.min.js"></script>
</body>
```
![container ejemplos](https://lh3.googleusercontent.com/proxy/m7HYUZ_9p7SWzGE1yFY47OEAqAb2jAc_7lwiYtTZZjAFKAW-oIg0RijuFZPpJI6sMYfrD3R_bQoPVGvOaz8lUyT6tYs3yTWeBRHrXAAB3HKSuMu6Oi1wvXE81g)

## container-fluid
la diferencia de este container es que etsa siempre establece el ancho maximo de el 100% de modo que se puede adptar a todo tipo de pantalla

```Ejemplo codigo```
```html
  <body>
  <div class="container-flui">
    <h1>Tyrone</h1>
  </div>
  <script src="js/jquery.js"></script>

  <script src="js/popper.js"></script>

  <script src="js/bootstrap.min.js"></script>
</body>
```
![container ejemplos](https://lh3.googleusercontent.com/proxy/vofiFQCxcACafDieXELLymYuVeVli3Mf6sCtgAuEV0iMP8GhWl_4Xxc1-3zCsH9ubaYKsnf6wugewmazQnTLJH_yw9iROs4zKdjtn7FbNhm97GQwh49gPNvxGA)







