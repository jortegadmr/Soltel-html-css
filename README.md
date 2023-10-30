---
favorited: true
pinned: true
title: README
created: '2023-10-24T11:58:31.228Z'
modified: '2023-10-25T12:19:06.753Z'
---

# Memoria

[//]: # (version: 1.0)
[//]: # (author: JAO)
[//]: # (date: 2023-10-28)


# Indice

- [Memoria](#memoria)
- [Indice](#indice)
  - [Enunciado](#enunciado)
  - [1- Extraer el contenido](#1--extraer-el-contenido)
  - [2- Crear HTML](#2--crear-html)
    - [HEADER](#header)
    - [Menu lateral](#menu-lateral)
    - [Articulo](#articulo)
    - [Footer](#footer)
  - [3- Maquetar con etiquetas semánticas](#3--maquetar-con-etiquetas-semánticas)
  - [4- CSS](#4--css)

<div style="page-break-after: always;"></div> 

## Enunciado

Desarrollo de la pagína web de Islantilla para el navegador Wikipedia. Vamos a seguir los siguientes pasos:

    1. Extraer el contenido en TXT de la página

	        https://onlinetexttools.com/extract-text-from-html
	
	        https://es.wikipedia.org/wiki/Islantilla

    2. Crear el HTML islantilla-wikipedia.html

    3. Maquetar con etiq. semánticas

    4. Crear el CS S externo y poner alguna regla islantilla.css

## 1- Extraer el contenido

Mediante distintas herramientas y páginas web: (https://onlinetexttools.com/extract-text-from-html) hemos extraído de la página de wikipedia el contenido en formato de texto. Se ha guardado en dentro de la carperta de recursos (SRC) con el fromato .txt

## 2- Crear HTML

Siguiendo el documento de texto le damos contenido a la página.

### HEADER

    - Introducimos la imagen del logo con la etiqueta <img> le damos los parámetro
    - Añadimos la barra de busqueda con la etiqueta <form>
    - Para el cuadro de texto utilizamos <input>
    - Para los enlaces se utiliza <a>
    - se ha añadido un menú principal como en la propia pagina original. Se ha utilizado una lista para ordenarlo <ul>

### Menu lateral

    Para el menu lateral se ha utilizado <aside>
En dicho menu de busqueda se ha vuelto a utilizar listas para el orden y se han nombrado los ID para las distintas secciones del articulo.

### Articulo

Para que exista un orden se ha procedido de la siguiente forma:

      <section> El articulo principal
        <article> Secciones dentro del articulo
          <p>       Los parrafos de texto
 
 Se hacen referencias a los ID puestos en el menu lateral para una búsqueda más fluida. Se han utilizado párafos y listas (numeradas y sin enumerar).

 Se ha utilizado la etiqueta SPAM para poner en cursiva "vease también" y "Artículo principal"

 ### Footer

 Se ha añadido información poco relevante

 ## 3- Maquetar con etiquetas semánticas

 Como se ha mencionado anteriormente se han utilizado las siguientes etiquetas

    <section>
    <article>
    
    <nav>
    <footer>

Se han añadido varias clases para su posterior uso en CSS

## 4- CSS

Se ha creado un archivo .CSS aparte, para dar formato a la página