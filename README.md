# Leaf-Lightbox

[Demostración](http://zkreations.github.io/Leaf-Lightbox/). Iconos por [Google Material icons](https://design.google.com/icons/)

## Instalación

[Descargar](https://github.com/zkreations/Leaf-Lightbox/archive/master.zip) e incluir arriba de `</head>` el codigo css.

```html
<link rel="stylesheet" href="leafbox.min.css"/>
<link rel="stylesheet" href="dist/theme/default.css"/><!--opcional-->
```
Si necesitas realizar alguna modificación, puedes hacerlo desde `leafbox.css` (la versión sin comprimir).

### Utilizar Leaf Lightbox

Crear un contenedor y un identificador, no importa mucho la etiqueta que utilices, puede ser section, header, figure, div, etc. Agregar la class **lbox [efecto]**, reemplazando [efecto] por uno de los preestablecidos: **fade, bounce, flip**. Para una imagen quedaria así:

```html
<figure id="img" class="lbox flip">
   <img src="img/img-03.jpg"/>
   <a href="#_"></a>
</figure>
```

Para video:

```html
<figure id="vid" class="lbox flip">
   <div class="vid">
       <!--player-->
   </div>
   <a href="#_"></a>
</figure>
```

Para texto:

```html
<figure id="text" class="lbox flip">
   <div class="text">
       <!--text-->
   </div>
   <a href="#_"></a>
</figure>
```

Ahora solo falta crear un enlace que apunte al identificador del contenedor.

```html
<a href="#img">Leafbox</a>
```

## Limitaciones

* No es posible incrustar mas de un elemento por cada contenedor.