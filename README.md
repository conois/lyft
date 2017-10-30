# Lyft

* **Track:** _Common Core_
* **Curso:** _Creando tu primer sitio web interactivo_
* **Unidad:** _Maquetado web con HTML & CSS_

***

Para completar este reto, hemos creado este repositorio boilerplate (plantilla
inicial) con todos los recursos que necesitas. Esto incluye imágenes y
estructura de carpetas y archivos donde colocarás tu código.

## Flujo de trabajo

1. Debes realizar un [**fork**](https://gist.github.com/ivandevp/1de47ae69a5e139a6622d78c882e1f74)
   de este repositorio.

2. Luego deberás **clonar** tu fork en tu máquina. Recuerda que el comando a usar
   es `git clone` y su estructura normalmente se ve así:

   ```bash
   git clone https://github.com/<nombre-de-usuario>/lyft.git
   ```

## Objetivo

El reto consiste en replicar el sitio de **Lyft**, este será el resultado
a lograr:

![Lyft Website](docs/fullpage.png)

## Consideraciones

* Encontrarás un archivo base `index.html` en el cual deberás escribir la
  estructura de tu proyecto y enlazar tus archivos de estilos (CSS).

* En la carpeta `css` tendrás un archivo base `main.css` donde agregarás los
  estilos necesarios para tu proyecto:

* Dentro de la carpeta `assets` se encuentra la carpeta `images` donde
  encontrarás todas las imágenes necesarias para completar tu proyecto.

* Deberás **actualizar el archivo `README.md`** explicando el contenido de tu
  repositorio.

* Esta web utiliza la tipografía `Montserrat`.

* La paleta de colores puedes obtenerla inspeccionado el sitio original, pero
  para ganar tiempo, puedes usar los siguientes:

  - Botones, hover: `#FF00BF`
  - Fondo de `footer`: `#333447`
  - Título del formulario: `#352384`
  - Texto del formulario: `#728099`
  - Gradiente morado: `linear-gradient(#76278F, #2B1E66);`

* Para el footer, deberás tomar en cuenta que tiene un hover y se ve como en la
  siguiente imagen:

  ![Lyft - Footer](docs/footer.gif)

  Además, los íconos deberás obtenerlo de `Icomoon`.

* Para este reto, encontrarás ciertas cosas que probablemente aun no has visto
  en clase (formularios, videos de Youtube). No te preocupes, estamos seguros
  que los afrontarás con éxito, de igual forma aquí unos tips:

  - Estos son los videos de Youtube:
    * https://www.youtube.com/watch?v=fLSmUWOYpKw
    * https://www.youtube.com/watch?v=V7j8Aqxmbs8
    * https://www.youtube.com/watch?v=xj2VWLV0xCU
  - Para agregar los videos, averigua sobre la etiqueta `iframe`.
  - Para el formulario, revisa las etiquetas como `form` e `input`.

* Puedes ver el [sitio original](https://www.lyft.com/), sin embargo, su diseño
  ya ha cambiado en ciertas partes, así que tu fuente de verdad es la imagen que
  muestra el objetivo de este reto.

  > Nota: El sitio original tiene ciertos efectos y funcionalidades que
están fuera del alcance de este reto. Enfócate en obtener la maquetación
lo más parecido posible, usando lo aprendido en clase ;)

## A tener en cuenta

Este reto será evaluado sobre lo siguiente:

* Pixel perfect (replicar el diseño con exactitud)
* Estructura de carpetas y archivos
* Nombramiento de clases, id, etc
* Indentación
* Archivo `README.md` actualizado y correctamente redactado
* Uso de comentarios para hacer tu código más legible

------------------------------------------------------------------------
## Modificacion archivo 

* El reto consistia en duplicar en "perfect pixel" la pagina de Lyft, para esto se trabajo bajo dos archivos, un index.html y un main.css, con el primero se da la estructura de nuestra pagina web mientras que con el archivo css damos estilo a esta. 

* Respecto al archivo HTML. 
Se uso la estructura semantica header y section para diferenciar las partes que se distinguian en la pagina. No se usó footer como estructura porque la pagina tendio a tener comportamiento espacial al usar esta estructura (no se si por error 400 o que ). Dentro de cada seccion se usaron divs para la organizacion de la informacion y por la facilidad que estos dan para poder mover y situar textos, imagenes o videos dentro de la pagina, ademas que es de los recursos que mas dominio tenemos. 
Se usaron clases y id para poder dar estilo, el nombramiento fue muy complejo, ya que hay momemtos en que la creatividad no funciona. Un punto importante aqui que llevo a un error en cierto punto del desarrollo fue que en un principio se habia declarado una clase y avanzada la pagina se volvio a reescribir el valor de esta, sin percatarse que ya tenia parametros definidos antes, por lo que un extracto de la pagina tenia un comportamiento extraño, el error claramente fue corregido pero sirvió para tomar el peso del nombramiento de clases. 

* Respecto a main.css. 
Se usaron recursos de css como manejo de estilos de fuente, su grosor, tamaño, tambien transformaciones que se pueden realizar a estas. Manejo de elementos de formulario, focus, placeholder y pseudo clases dentro de la creacion de estos. Manejo de elementos como background y como acomodar el tamaño de la imagen segun el requerimiento. 
Se ordenó el css de igual forma que el archivo html que fue por secciones, todos los estilos que fueron aplicados dentro de una seccion se englobaron en un comnetario inicial que señala donde comienza. 