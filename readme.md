 `<!DOCTYPE html>`

Define el tipo de documento que se está utilizando, en este caso, HTML5.

---

# `<html>`

Es el elemento raíz de la página web. Todo el contenido del documento HTML debe estar contenido dentro de esta etiqueta.

---

# `<head>`

Contiene información no visible del documento, como la configuración de los metadatos, enlaces a archivos externos (CSS, JS), y el título de la página.

---

# `<title>`

Define el título del documento que aparece en la pestaña del navegador.

---

# `<body>`

Es donde se encuentran los elementos visibles de la página, es decir, el contenido que se muestra en el navegador.

---

# `<h1>`

Define el encabezado principal de la página, el cual se muestra con un tamaño de fuente grande y es importante para la estructura jerárquica del contenido.

```html
<h1>Titulo</h1>
    <h2>Titulo</h2>
    <h3>Titulo</h3>
    <h4>Titulo</h4>
    <h5>Titulo</h5>
    <h6>Titulo</h6>

```
<h1>Titulo</h1>
    <h2>Titulo</h2>
    <h3>Titulo</h3>
    <h4>Titulo</h4>
    <h5>Titulo</h5>
    <h6>Titulo</h6>
---

# `<p>`

Es un párrafo de texto. Se utiliza para contener bloques de texto.
```html

    <p>Parrafo</p>
    <p>Parrafo con <br />Salto de Linea</p>
    <pre>
Escribir texto con
        salto de linea
    </pre>
```
 <p>Parrafo</p>
    <p>Parrafo con <br />Salto de Linea</p>
   
---

# `<hr>`

Es una línea horizontal que se utiliza como separador entre contenidos.

---

# `<pre>`

Preserva el formato original del texto, tal como se escribe en el código. Es útil para mostrar código o texto que requiere un formato específico, como los saltos de línea y espacios.

```html
    <pre>
Escribir texto con
        salto de linea
    </pre>
```
 <pre>
Escribir texto con
        salto de linea
    </pre>
---

# `<ul>`

Es un contenedor para listas desordenadas, donde los elementos son precedidos por puntos (bullet points).

---

# `<ul><li>`

Dentro de una lista desordenada, se usan las etiquetas `<li>` (list item) para definir cada elemento de la lista.

# Ejemplo de como usar la etiqueta ul

```html
<ul>
<ul>
<li><a href="./contacto.html">Contacto</a></li>
<li><a href="./index.html">Home</a></li>
</ul>
```

---

# `<ol>`

Es un contenedor para listas ordenadas, donde los elementos se numeran automáticamente, comenzando desde el número 1.

---

# `<img>`

Se utiliza para insertar imágenes en la página. Puedes usarla de las siguientes formas:

### Ejemplo 1: Imagen desde una URL externa

```html
<img
  src="http://plus.unsplash.com/premium_photo-1695405363183-e55554168063?fm=jpg&q=60&w=3000&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8aW1hZ2VuJTIwZGlnaXRhbHxlbnwwfHwwfHx8MA%3D%3D"
  alt="Imagen de ejemplo"
  width="300"
  height="200"
/>
```

<img src="http://plus.unsplash.com/premium_photo-1695405363183-e55554168063?fm=jpg&q=60&w=3000&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MXx8aW1hZ2VuJTIwZGlnaXRhbHxlbnwwfHwwfHx8MA%3D%3D" alt="Imagen de ejemplo" width="300" height="200" />

### Ejemplo 2: Imagen dentro de local

```html
<img
  src="./assets/img/image.png"
  alt="Imagen de ejemplo"
  width="300"
  height="200"
/>
```

<img src="./assets/img/image.png" alt="Imagen de ejemplo" width="300" height="200" />
