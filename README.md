Taller III - Aplicaciones Web. (Adriana Arrua Fleitas)

1. Que es el servidor?
	Es un programa que es capaz de atender requisiciones y enviar una respuesta.

2. Que es un protocolo dentro de la informatica?
	En informática, un protocolo es un conjunto de reglas usadas por computadoras para comunicarse unas con otras a través de una red.

3. Que es un servidor web?
	Es un programa que es capaz de atender requisiciones y enviar una respuesta utilizando el protocolo HTTP.

4. Que es un cliente?
	El cliente es una aplicación informática o un computador que consume un servicio remoto en otro computador, conocido como servidor, normalmente a través de una red de telecomunicaciones.

5. Cual es el cliente  web por excelencia?
	El cliente web por excelencia es el navegador web.

6. Que es HTML?
	HTML es lo que se utiliza para crear todas las páginas web de Internet, provenientes de las siglas “Hipertext Mark Language" 
	Los diseñadores utilizan el lenguaje HTML para crear sus páginas web.

7. Que son las etiquetas?
	Las etiquetas HTML son fragmentos de texto rodeados por corchetes angulares < >, que tienen funciones y usos específicos y se utilizan para escribir código HTML. Las etiquetas o tags son la forma de escribir código HTML.

8. Cuales son las diferencias entre las etiquetas h1, h2, h3, h4, h5 ,h6?
	Puede que queramos empezar nuestra web o nuestro texto con un encabezado indicando el título del artículo, categoría, etc. Pues bien, para escribir encabezados disponemos de las etiquetas <h>.
	Esta etiqueta viene acompañada de un número, desde el 1 hasta el 6, predefiniendo éstos el tamaño del encabezado. Así, <h1> sería el encabezado más grande mientras que <h6> sería el más pequeño.
	A continuación mostramos un código ejemplo de los seis diferentes encabezados:
	<h1> Texto muy grande</h1>
	<h2>Texto grande</h2>
	<h3>Texto algo más grande de lo normal</h3>
	<h4>Texto normal</h4>
	<h5>Texto pequeño</h5>
	<h6>Texto muy pequeño</h6>

9. Con que etiqueta se agrega una imagen en un documento html? Ejemplos.
	Las imágenes dentro de una página web se incluyen utilizando la etiqueta <img>, que no tiene una etiqueta correspondiente de cierre. Ejemplo:<img src="http://www.aprenderaprogramar.com/images/logo.png" alt="Logotipo APR2">

10. Con que etiqueta se agrega un video en un documento html? Ejemplos.
	La etiqueta que se utiliza para agregar un video en html es <video>, su estructura es muy similar a la que se emplea con las imagenes,
	aunque en este caso si lleva la etiqueta de cierre.
	Ejemplo: <video src = video/fireworks_reducido.webm"<>/video>

11. Con que etiqueta se agrega un sonido en un documento html? Ejemplos.
	Su estructura es sencilla y es la siguiente:
   <audio></audio> <– dentro de estas tags ira nuestros archivos de sonido
    Por Ejemplo:
    Quiero reproducir la canción: Oasis – Stop Crying Your Heart Out (esta en formato MP3)
    entonces escribimos asi:
   <audio id=”reproductor” controls preload>
   <source src=”http://rojer.pp.ru/misc/music/Oasis_-_04_-_Stop_Crying_Your_Heart_Out.mp3″ type=”audio/mp3″ />
    </audio>

12. Cual es la funcion de la etiqueta doctype?
	La etiqueta DOCTYPE es la primera que aparece en cualquier documento HTML. Su función es la de informar al navegador sobre el tipo de documento que va a cargar así como de informar sobre la codificación de caracteres. Además ésta etiqueta es fundamental si queremos que nuestro fichero HTML sea validado.

13. Con que atributo se indica la imagen que se utiliza dentro de una etiqueta de imagen?
    El atributo SRC indica el fichero de imagen que se incluirá en el documento.

14. Como se indica al navegador que el documento esta escrito en idioma ingles?
    Para establecer el idioma en la pagina se usa el atributo lang para páginas servidas como HTML, y el atributo xml:lang para páginas servidas como XML. Ejemplo: el siguiente codigo: <html lang = "en">

15. Que es una lista ordenada?
	Una lista ordenada es casi idénticas a la lista no ordenada, salvo que en este caso los elementos relacionados se muestran siguiendo un orden determinado,  se define mediante la etiqueta <ol>, los elementos de la lista se definen mediante la etiqueta <li>, la misma que se utiliza en las listas no ordenadas.

16. Que es una lista no ordenada?
	Una lista no ordenada es un conjunto de elementos relacionados entre sí pero para los que no se indica un orden o secuencia determinados. La etiqueta <ul> encierra todos los elementos de la lista y la etiqueta <li> cada uno de sus elementos.

17. Como se indica un parrafo?
	En HTML para demarcar un párrafo se usa la etiqueta p, situándose la instrucción de inicio <p> al comienzo del párrafo y la instrucción de fin </p> tras la última frase.

18. Como se indica la negrita, la cursiva, el subrayado, el tachado, el subindice y el superindice?
	*Existen dos etiquetas que hacen que nuestro texto se convierta en NEGRITA.La primera es la etiqueta <b> y la otra es la etiqueta <strong>.
	*Para escribir un texto en CURSIVA se utiliza mucho la etiqueta <i> (que por supuesto debes cerrarla con la etiqueta </i>). También se la etiqueta <em>.
	*Para que la palabra o el texto quedara SUBRAYADO se usa el rodearlo con la etiqueta <u> y cerrarlo con su correspondiente etiqueta </u>.
	*Existen tres etiquetas que se han venido usando para conseguir que un texto quede TACHADO. Hablamos de las etiquetas <strike>, <s> y <del>.
	*La etiqueta <sub> sirve para escribir un SUBINDICE y <sup> será la etiqueta para un SUPERINDICE.

19. Que es git?
	Git (pronunciado "guit" ) es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia y la confiabilidad del mantenimiento de versiones de aplicaciones cuando éstas tienen un gran número de archivos de código fuente.

20. Que es github?
	GitHub es una plataforma de desarrollo colaborativo de software para alojar proyectos utilizando el sistema de control de versiones Git.

21. Que es clonar un repositorio, cual comando se utiliza?
	Clonar un repositorio significa bajarse una copia completa del mismo a nuestro a ordenador. El comando que se utiliza es git clone"direccion url".

22. Que es un commint?
	Un commit es el comando utilizado guardar el archivo en el repositorio: git commmit [nombre del archivo]

23. Que es un push?
	Es agarrar los cambios y enviar al repositorio remoto.

24. Que es la rama master?
	Datos en el repositorio tras una serie de confirmaciones.Una rama Git es simplemente un apuntador móvil apuntando a una de esas confirmaciones. La rama por defecto de Git es la rama master . Con la primera confirmación de cambios que realicemos, se creará esta rama principal master apuntando a dicha confirmación.

25. Que es un repositorio local y remoto?
	Un repositorio local esta compuesto por tres "árboles" administrados por git. El primero es la Directorio del trabajo que contiene los archivos, el segundo es el Index que actua como una zona intermedia, y el último es el HEAD que apunta al último commit realizado.
	Los repositorios remotos son versiones de un proyecto que se encuentran alojados en Internet o en algún punto de la red. Pueden haber varios, cada uno de los cuales puede ser de sólo lectura, o de lectura/escritura, según los permisos que tengamos. 

 Responder y guardar el archivo con el nombre README.md (markdow)