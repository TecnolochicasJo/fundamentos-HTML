# Fundamentos de HTML
![HTML](https://raw.githubusercontent.com/TecnolochicasJo/fundamentos-HTML/main/imagenes/html.png)

## ¿Qué es HTML?
HTML (Lenguaje de Marcas de Hipertexto, del inglés HyperText Markup Language) es el componente más básico de la Web. <br>
Define el significado y la estructura del contenido web. Además de HTML, generalmente se utilizan otras tecnologías <br>
para describir la apariencia/presentación de una página web (CSS) o la funcionalidad/comportamiento (JavaScript).

## [ Link al código](https://github.com/TecnolochicasJo/fundamentos-HTML/blob/main/index.html)
![Código]( https://raw.githubusercontent.com/TecnolochicasJo/fundamentos-HTML/main/imagenes/codigoEtiquetasHTML.PNG)

## Etiquetas que falto por ver en la sesión Fundamentos de HTML del dia Sabado 29 de Octubre
- **Casillas de verificación:** Funcionan para elegir mas de una opción.<br> Para este caso lo unico que cambia es el tipo del input 
    es decir, ya **no** sera ```<input type="text">``` <br> sino que cambiara el tipo **text** por **checkbox** quedando de la siguiente manera 
    ```<input type="checkbox">``` y porsupuesto se agregan más atributos. <br>
    Ejemplo: 
```html
    <p>¿Qué tipo de musica canta tu artista favorito?</p>
    <label for="k-pop">
        <input type="checkbox" id="k-pop" class="k-pop" name="tipoMusica" checked>K-pop
    </label>
    <br>
    <label for="Rock">
        <input type="checkbox" id="rock" class="rock" name="tipoMusica" >Rock
    </label>
    <br>
    <label for="mariachi">
        <input type="checkbox" id="mariachi" class="mariachi" name="tipoMusica">Mariachi
    </label>
    <br>
    <label for="banda">
        <input type="checkbox" id="banda" class="banda" name="tipoMusica">Banda
    </label>
    <br>
    <label for="rap">
        <input type="checkbox" id="rap" class="rap" name="tipoMusica" >Rap
    </label>
    <br>
    <label for="pop">
        <input type="checkbox" id="pop" class="pop" name="tipoMusica" >Pop
    </label>
    <br>
```

<br>

![checkbox](https://raw.githubusercontent.com/TecnolochicasJo/fundamentos-HTML/main/imagenes/checkbox.PNG)

- **Etiqueta ```<div></div>```** Sirve para crear secciones o agrupar contenidos. Por el momento no se visualizara nada en la pagina,
    se podrá ver su función cuando se haga uso de los estilos con CSS.<br>   
    Ejemplo: 
```html
    <div>
        <p>Cosas que los integrantes de BTS aman</p>
        <ul>
            <li>Tacos</li>
            <li>Tequila</li>
            <li>Chicas</li>
            <li>Gatos</li>
            <li>Perros</li>
            <li>Bailar</li>
            <li>Bromas</li>
        </ul>
    </div>
```

<br>

En este caso solo se muestra el contendido que esta dentro del **div**<br>
![div](https://raw.githubusercontent.com/TecnolochicasJo/fundamentos-HTML/main/imagenes/div.PNG)

- **Etiqueta ```<footer></footer>```** Es para el pie de página. En el se coloca todo el contenido final, pueden ser links a redes sociales,  dirección/ubicación, derechos de autor de la página, contacto, etc. <br>  
Ejemplo:

```html
    <footer>
        <!-- etiqueta <small> para letras pequeñas -->
        <p><small>Derechos de autor - <a href="https://tecnolochicas.mx/" target="_blank">tecnolochicas.mx</a></small></p>
        <p><small>Pagina diseñada por Luz</small></p>
    </footer>
```
<br>

![footer](https://raw.githubusercontent.com/TecnolochicasJo/fundamentos-HTML/main/imagenes/footer.PNG)

- **Etiqueta ```<small></small>```** Es para hacer más pequeña la letra. <br> Ejemplo: 

```
    <p><small>Pagina diseñada por Luz</small></p>
```

## Para saber mas sobre HTML puedes visitar los siguientes links
- [Etiquetas y elemento HTML](https://www.w3schools.com/TAGS/default.asp)
- [HTML](https://developer.mozilla.org/es/docs/Web/HTML)
