# AW
ejercicios clase Aplicaciones Web

- estructura mínima de una web
```html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```

- explica las 3 formas de usar CSS en HTML
```html
Interno: El interno es creando una etiqueta de style y aplicandolo en la etiqueta deseada, por ejemplo 
<style>
p {
	text-align: center
}
</style>

Externo: Creamos un archivo con extension .css con los estilos que queremos aplicar y lo instertamos en nuestro codigo de esta manera
 <head>
<link rel="style" type="text/css" href="rutaDelArchivo.css">
</head>

En linea: Se coloca el codigo en la misma linea de la etiqueta
<p style="color:red; font-size:10px;> esto es un css en linea</p>
```
- crea una lista sin ordenar con 5 ingredientes de una receta de cocina
```html
<ul>
	<li>Arroz</li>
	<li>Pollo</li>
	<li>Conejo</li>
	<li>Judia Ancha</li>
	<li>Garrofon</li>
</ul>
```
- como se puede incluir javascript en HTML
```html

```
- ¿Que diferencia hay entre una clase y una ID
- código para hacer un enlace a otra página y que esta se abra en una nueva ventana
- ¿Qué son las pseudoclases?, pon ejemplos.
- Explica el modelo de caja de CSS (margin, border y padding)
- Explica que son los selectores de CSS y pon ejemplos
- Di a quien afectan:

    p a { color: red;

    p > a { color: red; }

    h1 + h2 { color: red }

    a[class] { color: blue; }

    a[class="externo"] { color: blue; }

    a[href="http://www.ejemplo.com"] { color: blue; }
