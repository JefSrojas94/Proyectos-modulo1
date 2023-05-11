# Intro a la web
## recordar la estructura de HTML

1. `<head> </head>`: metadatos, Cabecera, configuraciones, titulo
2. `<body> </body>`: estructura visual de la pagina.El Contenido

## Utilizar etiquetas semánticas:
```
<header>
    <nav></nav>
</header>
<main>
    <section></section>
    <aside></aside>
</main>
<footer></footer>
```

    - NOTA: si quieres dar orden a documento click derecho y format document
## empieza a añadir etiquetas q se requieran, no olvidar dar atributos.
1. Atributos en comun:
    - class: etiqueta para clasificar elementos, ej:
        -  `<p class="primero">`
        -  `<p class="primero bg-negro">`
        -  `<p class="primero texto">`
        - una etiqueta puede tener tantas clases requiera, minetras se separen por un espacio.
    - id: identificador unico que se asigna a una etiqueta y asi poder acceder directamente a ellos. 
## Agrega estilos
    - inline
    - interno
    - externo: Es importar los estilosque viven en un archivo fuera del HTML con la extensión `.css`, siguendo estos pasos:
    1. crear archivo: `styles.css`
    2. enlazar con HTML poniendo en el encabezado `links:css` y enter.
    3. usar selectores para dar estilos:
        - nombre de la etiqueta: `p`
        - clase: `.nombre_de_la_clase`
        - id: `#identificador`
        - Prioridad de CSS en estilos:
          !important
          Estilos en linea
          #Id
          Clases, atributos y pseudoclases
          Elementos y pseudoelementos
          selector universal