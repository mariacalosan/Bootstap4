
  <!--la class container lo que hace es que me va a sentrar lo que yo tenga en el bloque esto lo genera bootstrap hay otro  tipo de contenedor que es para el ancho completo que serai en container-fluid -->
<!--  <div class="container">-->
    <!--en esta parte de el index y de el curso estamos viendo como es la creacion de columnas va todo dentro de este div con la clase row que en español es filas-->
    <!--<div class="row">-->
     <!--creacion de la columna dentro de est div agregue mi h1 y el parrafo  de esta manera se puede pocisionar elementos en la pagina si quisiera mas elementos en mi fila lo podria hacer como este codigo -->
     <!--le indique asta donde queria que estuviera el contenido de la columna ahora le quiero indicar el largo con la fincion col-lg le puedo indicar el largo que quiero en la columna -->
   <!--   <div class="col-2 col-sm-4 col-lg-2">
          <h1>divertilandd</h1>
          <p>
            lorem hello hola gente como estamos el  dia de hoy
          </p>
      </div>
    </div>
  </div>-->

  <!--<div class="container">
    <div class="row">
      <div class="col columna">1</div>
      <div class="col columna">2</div>
      <div class="col columna">3</div>
      <div class="col columna">4</div>
      <div class="col columna">5</div>
      <div class="col columna">6</div>
      <div class="col columna">7</div>
      <div class="col columna">8</div>
      <div class="col columna">9</div>
      <div class="col columna">10</div>
      <div class="col columna">11</div>
      <div class="col columna">12</div>
    </div>
  </div>-->

  <!--vinculacion de el jquery para boostrap este se debe de vincular antes de vincular js -->
  <!--<script src="estilos/js/jquery.js"></script>-->
  <!--vinculacion de el popper este debe ir antes de bootstrap y despues de jquery-->
  <!--<script src="estilos/js/popper.js"></script>-->
  <!--vinculacion de el srchivo de js de bootstrap-->
  <!--<script src="estilos/js/bootstrap.min.js"></script
  con la clase de col-auto solo metoma el espacio donde esta el texto

halladiendo el offset  el offset es basicamente el espacio que se puede añadir en blanco este siempre va a añadir columnas en blanco hacia la izquierda

tipografias etiqeuta small es para poner extosa mas pequeño
clase display esta clase lo que haces es que cambia de forma Cambie de forma rápida y sensible el valor de visualización de los componentes y más con nuestras utilidades de visualización hace el los titulos mas grades

continuacion con la tipografia
etiqueta mark  es representada con un color de fondo amarillo y algo de relleno:
etiqueta del o etiqueta s lo que hacesn es tachar el texto
etiqetas para subrayar el texto la etiqueta ins y la etiqueta U
etiqueta strong lo que hace es poner el texto en negrita
etiqueta em para poner el texto en tipo italica
el texto tan bien se puede aliniar pormedi de clases
clas=" text-left"
clas=" text-center"
clas=" text-right"
clas=" text-justify"
capitalizacion de texto la capitalizacion de texto sirve para poner la primera letra de le texto en mayuscula
texto en minuscula con text-lowercase
para todo el texto en mayuscula es uppercase
clase para cambair el fondo de la letra
ejemplos de los tipos de atributos para la tipografia en codigo
   <p class="text-left font-weight">Lorem ipsum dolor sit amet.</p>
        <p class="text-right">Lorem ipsum dolor sit amet.</p>
        <p class="text-justify">Lorem ipsum dolor sit amet.</p>
        <p class="text-capitalize">Lorem ipsum dolor sit amet.</p>
        <p class="text-uppercase">Lorem ipsum dolor sit amet.</p>
        <p class="text-lowercase">Lorem ipsum dolor sit amet.</p>
        <p class="text-center">Lorem ipsum dolor sit amet consectetur adipisicing elit. Temporibus, cumque! Officiis, voluptatibus facere. Aliquam nesciunt repudiandae sit ut dolore officia provident, aut unde, velit autem libero labore sint pariatur fugiat expedita necessitatibus in, hic laudantium! Iure, voluptatibus velit in dolores natus animi maiores autem cupiditate, corrupti vel totam blanditiis illum. Commodi, molestias hic quidem facere eos distinctio. Laboriosam illo fuga nemo placeat ad quasi accusamus pariatur reiciendis aliquam! Laudantium dolorum laborum aperiam possimus, quasi repellat voluptate doloremque vitae ad inventore corporis mollitia error iure, quae quidem quos in, quis suscipit magnam odio. Rerum impedit, numquam non maxime minima autem placeat.
    </p>
<div class="mt-4">
        <p> Lorem ipsum <mark>dolor</mark>sit amet.</p>
        <p>Lorem ipsum <del> sit</del> <s>amet</s></p>
        <p>Lorem <ins>ipsum</ins> dolor <u>amet</u>.</p>
        <p>Lorem <strong>dolor </strong> sit amet.</p>
        <p>Lorem <em>dolor</em> sit amet.</p>
      </div>
etiqueta blockquote esta etiqueta es para Crea citas en bloque, marca las citas a otros autores o documentos. este tambien esta como clase en bootstrap

como mostrar codigo de una maneras facil para los usuarios

como manipular imagenes por medio de clases
class="img-fluid" esta clase lo que hace es que añade un max-widht de el 100% y el heigth lo pone en auto
class="img-thumbnail" esta se encarga de darle una apariencia a la imagen un poco mas estilo de catalogo
class="img-runded" para darle un estilo a la imagen mas redindeao el borde
ejemplo en codigo de como implementas las clases 
<section
        class="
          row
          servicios
          justify-content-lg-around justify-content-xl-between
         ">
        <!--se agrego una nueva seccion para los serviciops de la pagina  -->
        <div class="servicio col-sm-6 col-md-4 col-lg-3">
          <h3 class="display">servicios</h3>
          <img class="img-rounded" src="estilos/img/tobogan.png" alt="tobogan">
          <p>me gusta la adrenalina</p>
        </div>
        <div class="servicio col-sm-6 col-md-4 col-lg-3">
          <h3>servicios</h3>
          <img class="img-thumbnail" src="estilos/img/tobogan.png" alt="tobogan">
          <p><small>me gusta la adrenalina</small></p>
        </div>
        <div class="servicio col-sm-6 col-md-4 col-lg-3 offset-1">
          <h3>servicios</h3>
          <img class="img-fluid" src="estilos/img/tobogan.png" alt="tobogan">
          <p>me gusta la adrenalina</p>
        </div>
      </section>
la imagen tan bien se puede añadir dentro una etiqueta figure
esta se le puede añadir texto un label que describa que es lo que esta en la imagen
ejemplo de como se veria en codigo

        <div class="row">
          <div class="col">
            <figure class="figure">
              <img class="img-fluid" src="estilos/img/calzado.jpg" alt="calzado">
              <figcaption class="figured-caption">este son los zapatos </figcaption>
            </figure>
          </div>
        </div>
      </section>

<!--tablas-->
se pueden crear de la forma tradiciona que seria con la etiqueta table despues de eso le puedes hacer la estructura normal e la tabla agregando filasy columnas de una forma semantica con las etiquetas de thead para el encabezado de la pagina y tbody para el cuerpo de la tabla dentro de la etiqueta pondras la etiquetatr que es la tebolrode que esta significa que define una fila de celdas en una tabla. dentro de esta etiqueta se vendria poniendo lo que seria los th que esta etiqueta seria de  define una celda como encabezado de un grupo de celdas en una tabla
con la etiqueta td lo que haces es que define la celda de una tabla que contiene datos
si le quieres implementar estilos a la etiqueta table le puedes añadir una clase llamada table y si le quieres dar un etilo diferente le puedes poner la clase table-dark ya tu juegas con esta clase como lo desees si solo quieres quetenga ese estilo en en encabezadoi de la tablapones la clase en el thead si no quieres el estilo de dark lo puee cambiar por le de table-light
class="table table-stripe" para agregar rayas de cebra a cualquier fila de la tabla dentro del tbody
lass="table table-borderd" para bordes en todos los lados de la tabla y las celdas.
class="table table-hover" para habilitar un estado de desplazamiento en las filas de la tabla dentro de un tbody.
class="table table-sm" esto es para la tabla mas pequeña
para añadir color como lo hacia en con los textos tabien hat¿y clases especificas para esto como
tr class="table-primary">...tr>
tr class="table-secondary">...tr>
tr class="table-success">...tr>
tr class="table-danger">...tr>
tr class="table-warning">...tr>
tr class="table-info">...tr>
tr class="table-light">...tr>
tr class="table-dark">...tr>
como hacer una tabla responsiva
class="table-responsive"
aprendiendo a utilizar el media object  es un elemento de bootstrap que permite la creacion de contenido repetitivo en las paginas

