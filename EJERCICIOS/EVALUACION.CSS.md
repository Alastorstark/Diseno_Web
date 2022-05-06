5. LENGUAJE CSS
Objetivo: Verificar el dominio de implementación de estilos (CSS) sobre el código html de una página web.

Indicaciones: Pedir subrayar, encerrar en un círculo, o escribir la respuesta que consideren correcta.

Preguntas:

¿Qué significa CSS? (valor 0.25)

     a) Cascading Style Sheets
    
   
¿Cuál es el HTML correcto para hacer referencia a una hoja de estilo externa? (valor 0.25)

    
     b) <link rel="stylesheet" type="text/css" href="style.css">
    
  
¿En qué parte de un documento HTML es el lugar correcto para hacer referencia a una hoja de estilo externa? (valor 0.25)

     a) En la sección <head>
    
  
¿Qué etiqueta HTML se utiliza para definir una hoja de estilo interna? (valor 0.25)

    
    c) <style> 
    
¿Qué atributo HTML se usa para definir estilos en línea? (valor 0.25)

    
    b) styles
  
¿Cuál es la sintaxis CSS correcta? (valor 0.25)

    
    b) body {color: black;}
    
    
¿Cómo se inserta un comentario en un archivo CSS? (valor 0.25)

    a) /* esto es un comentario */
   
    
¿Qué propiedad se utiliza para cambiar el color de fondo? (valor 0.25)

    
     b) background-color
    
¿Cómo se agrega un color de fondo para todos los elementos h1 (valor 0.25)

   
     b) h1 {background-color:#FFFFFF;}
    
     
¿Qué propiedad CSS se usa para cambiar el color del texto de un elemento? (valor 0.25)

   
    c) color
    
¿Qué propiedad CSS controla el tamaño del texto? (valor 0.25

       
       c) font-size
      
   
¿Cuál es la sintaxis CSS correcta para poner en negrita todos los elementos p?(valor 0.25)

    
     c) p {font-weight:bold;}
     
     
¿Cómo hacer que cada palabra en un texto comience con una letra mayúscula? (valor 0.25)

    
    b) text-transform:capitalize
    
     
¿Qué propiedad se utiliza para cambiar la fuente de un elemento? (valor 0.25)

    
    b) font-family
    
     
¿Cómo pones el texto en negrita? (valor 0.25)

 
    c) font-weight:bold;
     
¿Cómo se muestra un borde como este? (valor 0.25)

    El borde superior = 10 píxeles

    El borde inferior = 5 píxeles

    El borde izquierdo = 20 píxeles

    El borde derecho = 1 píxel

            a) border-width:10px 1px 5px 20px;
            (valor 0.25)
     
¿Qué propiedad se usa para cambiar el margen izquierdo de un elemento? (valor 0.25)

      
      b) margin-left
     
Al usar la propiedad de relleno (padding); ¿Está permitido usar valores negativos? (valor 0.25)

    
      b) Sí
      
     
¿Cómo se selecciona un elemento con id 'demo'? (valor 0.25)

     
     b) #demo
    
     
20.¿Cómo se seleccionan elementos con el nombre de clase 'test'? (valor 0.25)

          
          b) .test
          
     
¿Cómo se seleccionan todos los elementos p dentro de un elemento div? (valor 0.25)

      
      b) div p
     
     
22.¿Cómo se agrupan los selectores? (valor 0.25)

          
          c) Separe cada selector con una coma
     
¿Cuál es el valor predeterminado de la propiedad posición? (valor 0.25)

    a) absolute
   
     
24.¿Cómo se hace una lista que enumere sus elementos con cuadrados? (valor 0.25)

        
        c) list-style-type: square;
     
Realiza la maquetación del siguiente ejemplo de página: (se aplica la rúbrica de la maquetación en código html y css, valor 36)


  ![image](https://user-images.githubusercontent.com/87988894/166944537-8d4893c5-e243-4b97-b53e-2dfbf1949da0.png)
  ![image](https://user-images.githubusercontent.com/87988894/166949662-478a5f1e-bf3e-4f78-bbfc-e84cdd991e99.png)



image

  ● Este ejercicio lo deberás realizar con las etiquetas de HTML5, haciendo uso de los elementos semánticos de HTML5.

  ● Deberás, en un bloc de notas, colocar todo el código html5 y guárdalo con extensión .html

   ● Lo mismo harás con el código CSS3, deberás guardar en un bloc de notas el código css3 con extensión .css.

   ● Guardar ambos archivos, el código html5 y css3, en una misma carpeta.

   ● Recuerda usar el elemento link para llamar dentro del código html5 los estilos guardados en el archivo con extensión .css.

   -Hay tres imágenes que utilizarás para realizar esta actividad: Imagen del logo institucional. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/assets/images/logo.svg

   Imagen del vector blanco que se encuentra antes del texto “Aprende a programar”. https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero-vector.svg

   Imagen paisaje de la Ciudad de México https://escuelasdecodigo.cdmx.gob.mx/wp-content/themes/escuelasdecodigo/dist/assets/hero.jpg

  -El texto alternativo para la primer imagen imagen debe ser “Gobierno de la Ciudad de México”

   INGRESA AQUI EL CÓDIGO HTML
                                                    
      <!DOCTYPE html>
     <html>
       <head>
         <link rel="stylesheet" href="estilos.css">
       </head>
       <body>
          <header>
          <div id="logo">
               <img src="logo.svg" alt="logotipo">
          </div>
          <div id="lista">
               <ul>
                  <li><a href="">Residentes </a></li>
                  <li><a href="">Negocios</a></li>
                  <li><a href="">Visitantes</a></li>
                  <li><a href="">Gobierno</a></li>
             </ul>
          </div>
          </header>
          <div class="cuadro">
             <div id="contenedor">
               <h1 id="text">>APRENDE A PROGRAMAR<br> EN LA <strong class="grande">ESCUELAS</strong><br>  DE <strong class="grande">CÓDIGO</strong><br>  DE LA CDMX</h1>
             </div>
         </div>

          <footer>
               <div id="foot">
                  <h2 id="naranja">¿Quien se puede inscribir?</h2>
                  <p><strong>Cualquier persona que quiera aprender a programar código y cuente con 4-8 horas disponibles  a la semana</strong></p>
                        <p>"Menores de edad deberan entrar a las instalaciones acompañados por un adulto."</p>
               </div>
          </footer>

       </body>
     </html>
      
      
   INGRESA AQUI EL CSS
   
             *{
              margin: 0%;
              padding: 0%;
          }
          body{
              background-color:white;
          }
          /* header */
          header{
               width: 100%;
              justify-content: space-between;
              display: flex;

          }
          a{
              text-decoration: none;
              color:rgb(9, 80, 9);

          }
          #logo{
              width: 50%;


          }
          #lista{
              width: 50%;

          }
          ul{
              list-style: none;
              display: flex;
              align-items: flex-end;
              justify-content: end;
              text-decoration: none;
          }
          li{

              justify-content: space-between;
              margin: 20px;
              color: rgb(9, 80, 9);
              font-size: 1.5em;

          }
          /* main */
          .cuadro{
              background: url("hero.jpg");
              background-repeat: no-repeat;
              background-position:center ;
              background-size: cover;
              width: 100%;
              height: 70vh;
              text-align: right;
              align-items: center;
          }
          #text{
              color: white;
              font-size:3.5em;
              font-family: 'Times New Roman', Times, serif;
              text-align: right;
              align-items: center;
              padding-top: 200px;

          }

          #contenedor{
              width: 50%;
          }
          #grande{
              font-size: bold;
          }

          /* footer */
          footer{
              height: 10vh;
              width: 100%;
              text-align: center;
              justify-content: center;
              margin-top: 20px;
          }

          h2{
              color:rgb(173, 115, 7);
          }
          #foot{
              font-size: 2em;
              text-align: center;
              justify-content: center;

          }
Ingresa el link a tu página del proyecto final
