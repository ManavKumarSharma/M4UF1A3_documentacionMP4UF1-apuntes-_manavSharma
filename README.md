# M4UF1A3_documentacionMP4UF1_apuntes_manavSharma

# Apuntes GitHub

## Creación de un repositorio en GITHUB

Primero de todo accedemos a la página de [Github](URL "https://github.com/")
Después de crear e iniciar sesión en una cuenta, en el menu principal nos aparecerá un apartado dónde se puedan crear nuevos repositorios:

![Foto](FotosApuntes/Repositorio.jpg)

Dándole click nos llevará a crear nuestro repositorio:

![Foto](FotosApuntes/Repositorio2.PNG)

Nos aparecerá diferentes apartados:

1. Repository name --> El nombre del repositorio que deseamos darle.
2. Description --> Una breve descripción sobre nuestro repositorio y las actualizaciones que vayamos insertando.
3. Podemos ponerlo tanto público "public" como en privado "private".
4. ¡IMPORTANTE! --> Crear un archivo read.me para que podamos gestionar de manera correcta nuestro repositorio y que no tengamos ningún problema.

Una vez creado el repositorio podemos interactuar con él añadiendo archivos o configurando documentos desde la propia usando el lenguaje de MarkDOWN.

## Lista de comandos de MarkDOWN:

## Para crear encabezados:

![Foto](FotosApuntes/encabezado.PNG)

### Resultado:

# Encabezado 1 (h1)
## Encabezado 2 (h2)
### Encabezado 3 (h3)
###### Encabezado 6 (h6)

## Para crear textos según cursiva-negrita:

![foto](FotosApuntes/textos.PNG)

### Resultado:

*Este texto aparece en cursiva*

_Este texto aparece en cirsuiva_

**Este texto aparece en negrita**

_**Este texto aparece en negrita y en cursiva**_

__Este texto aparece en negrita__

## Para crear listas no-ordenadas/ordenadas:

![Foto](FotosApuntes/Lista.PNG)

### Resultado:

Lista ordenada:
1. Titulo1
2. Titulo2

Lista ordenada con subtítulos:
1. Titulo1
    1. Subtitulo1
    2. Subtitulo2
    3. Subtitulo3
2. Titulo2

Lista desordenada:

* Titulo1
- Titulo2
+ Titulo3

## Para crear una secuencia de códigos HTML y poder copiarlos:

![Fotos](FotosApuntes/HTML.PNG)

### Resultado:

```html
<html>
  <head>
  </head> 
</html>
```

## Para poner links o fotos:

![Foto](FotosApuntes/Links.PNG)

### Resultado:

[Enclace a wikipedia](URL "https://es.wikipedia.org/wiki/Wikipedia:Portada")
![Foto](FotosApuntes/1200px-Wikipedia-logo-v2.svg.png)

## Para crear tablas:

![](FotosApuntes/tabla.PNG)

### Resultado:

| Encabezado 1 | Encabezado 2 | Encabezado 3 |
| ------------ | :----------: | -----------: |
| Item1        | Boligrafos   | 20 euros     |
| Item2        | Lavadora     | 1000 euros   |
| Item3        | Lapices      | 50 euros     |


# GitHUB y CMD

[GitHub](URL "https://github.com/") es un sitio "social coding" dónde te permite subir repositorios de código para almacenarlo en el sistema de controles [GIT](URL "https://git-scm.com/").

![](FotosApuntes/GIT.PNG)

## Utilización de GIT en CMD
Para acceder al CMD debemos ir al **WINDOWS** y escribir CMD que es la ventana de comandos de Windows.

![](FotosApuntes/cmd.PNG)

Una vez accedido, nos aparecerá una ventana con el símbolo del sistemade.

![](FotosApuntes/cmd2.PNG)

Tenemos el caso que nos hemos creado un repositorio de prueba llamado _aprendizajeMarkdown_. Nos interesa hacer una copia de este repositorio en nuestro equipo. Primero de todo copiamos la URL del repositorio. Recalcar que anteriormente hemos creado una carpeta llamado _repositorios GIT_ dentro del disco C:.

![](FotosApuntes/copialinkrepositorio.PNG)

Una vez copiado el link del repositorio, nos dirigimos al CMD y navegamos por el de la siguiente manera:
### Moverse por CMD por rutas:

cd.. --> Ir una carpeta atrás.

dir --> "Directory" --> Mostrar todo lo que contiene la carpeta.

Mkdir --> Crear una carpeta.

Rd --> Eliminar un archivo.

Cd ./“nombre de la carpeta” --> Entrar en la carpeta directamente si necesidad de pasa una por una.

Una vez sabemos esto, nos interesa ir al disco C:, repositorios GIT y clonar el repositorio que hemos copiado de la siguiente manera:

![](FotosApuntes/cmd3.PNG)

Hemos llegado al disco C: y procedemos a entrar a _repositorios GIT_ y clonar con el comando _git clone_ que sirve para clonar el repositorio, de esta manera crea una carpeta con todo lo contenido del repositorio.

![](FotosApuntes/cmd4.PNG)

![](FotosApuntes/carpeta1.PNG)

Para poder subir los archivos que vayamos añadiendo en la carpeta _aprendizajeMarkdown_ a GitHUB debemos primero sincronizar la carpeta con el repositorio.
En este caso hemos añadido un bloc de notas llamado _ArchivoPrueba_.

![](FotosApuntes/carpeta2.PNG)

Para sincronizarlo debemos poner el comando _git init_, después con el comando _git add ArchivoPrueba.txt_ estamos añadiendo el archivo prueba. Una vez añadido el archivo, lo empaquetamos con el comando _git commit -m "descripción"_, en este caso nuestra descripción es "añadir archivo". Empaquetarlo es poner todos los archivos añadidos en un paquete. Por último subimos el archivo con el comando _git push origin main_ que nos subirá el archivo a nuestro repositorio.

![](FotosApuntes/cmd5.PNG)

![](FotosApuntes/archivoprueba.PNG)

# HTML:

**HTML** es un lenguaje de marcas que se utiliza para estructurar y desplegar una página web y sus contenidos.
En nuestro caso para utilizar html descargaremos [VISUAL STUDIO CODE](URL "https://code.visualstudio.com/"), un editor de codigo fuente que nos dejará interactuar con HTML.

## BÁSICO HTML:

```html

<!DOCTYPE html>                                                             <!-- Tipo de documento que va a ser -->
<html lang="es">                                                            <!-- A partir de aquí es todo html (lang = "es") Atributo de la etiqueta -->
<head>
    <meta charset="UTF-8">                                                  <!-- "UFT-8" Tiene "ñ", "ç", "accentos", etc. -->                                                       
    <meta http-equiv="X-UA-Compatible" content="IE=edge">                           
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página web</title>
</head>
<h1>Encabezado 1</h1>
<div>
<body>
    <!-- Mi primer párrafo -->
    <p id="pararafo1" class="Informacion" style="CSS" title="Info"> Te levantas por la mañana. Es un día cálido, los pájaros cantan, piensas en preparar café, pero antes te metes al baño para darte una ducha. Mientras cae el agua sobre tus ojos, ves cómo los azulejos de la pared empiezan a brotarse, como si quisieran salirse de su lugar. Piensas que es una ilusión óptica. Te secas los ojos y continúas viendo lo mismo. Con un poco de nervios, tocas los azulejos y compruebas que están en su puesto, y que no se han movido ni medio centímetro. Están firmes, como siempre. </p>
    <h2>Encabezado 2</h2>
    <p><em> Esto esta en cursiva </em> <!-- cursiva --> <strong> Esto esta en negrita </strong> <!-- Negrita --> Cuando pasa la luz y abres los ojos, todo se ha vuelto oscuro. No ves nada. Te agarras del árbol, y comprendes que debes aguantar de esta manera. Sin agua, sin alimento, sin huir, simplemente quedándote quieta junto al árbol, meditando, estando en ti. Sin miedos, sin apegos. Estás sola, como cuando viniste al mundo. La muerte no siempre es física, a veces, los vivos atraviesan la muerte y regresan de ella sanos y salvos. </p>
    <br> <!-- Salto de línia -->
    <hr> <!-- Salto de línia con una línia visible -->
    <p>Cuando pasa la luz y abres los ojos, todo se ha vuelto oscuro. No ves nada. Te agarras del árbol, y comprendes que debes aguantar de esta manera. Sin agua, sin alimento, sin huir, simplemente quedándote quieta junto al árbol, meditando, estando en ti. Sin miedos, sin apegos. Estás sola, como cuando viniste al mundo. La muerte no siempre es física, a veces, los vivos atraviesan la muerte y regresan de ella sanos y salvos. </p>
    <strong><em>Negrita y cursiva</em></strong> 
</div>

<div>
    <h1>Receta</h1>
    <ul>
        <li>Ingradientes</li>
            <ol>
                <Li>3 Huevos</Li>
                <li>200 gr de harina</li> 
            </ol> 
        <Li>Paso a paso</Li>
            <ol>
                <li>Romper los Huevos</li>
                <li>Batir los Huevos</li>
            </ol>
    </ul>
    <a href ="img/videos/home.html">Enlace a página 2</a> <!-- Enlaces... Ir a una carpta: /algo/ALGO... Viceversa: ../ALGO para retroceder a algo. -->
    <img src="" alt=""/> <!-- Etiqueta especial src: Buscar o definir dónde está ubicada la imagen/ alt: Cuando no se muestra la imágen, aparezca un texto alternativo-->
</div><!-- Definir un bloque --> <!-- IMPORTANTE! -->
</body>

</html><!-- Aquí finaliza el html --> 

```

### RESULTADO:

![FOTO](FotosApuntes/ApuntesHTML.PNG)




