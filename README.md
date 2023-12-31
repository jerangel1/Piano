
<h1>Web adaptativo construyendo un piano</h1>

<img src="./ImgPiano.png" alt="Preview del piano">

Este código HTML y CSS crea un piano simple con 25 teclas, 12 de las cuales son teclas negras. El piano tiene un logotipo de freeCodeCamp en la esquina superior izquierda.

<h2>Lógica del código</h2>

<ul>
  <li><b>El código HTML</b> crea la estructura básica del piano, con un elemento div para el piano en sí y un elemento div para las teclas.</li>
  <li><b>El elemento piano</b> tiene un fondo verde oscuro, un ancho de 992 píxeles, un alto de 290 píxeles y está centrado en la página.</li>
  <li><b>El elemento keys</b> tiene un fondo negro, un ancho de 949 píxeles y un alto de 180 píxeles.</li>
  <li>El código CSS se utiliza para estilizar el piano y las teclas.</li>
  <li><b>El elemento piano</b> tiene bordes redondeados y el elemento keys está oculto para que no se desborde del elemento piano.</li>
  <li>Cada tecla está representada por un elemento div con la clase key.</li>
  <li><b>Los elementos key</b> tienen un fondo blanco, un ancho de 41 píxeles, un alto de 175 píxeles y están separados por un margen de 2 píxeles.</li>
  <li><b>Los elementos key</b> también tienen bordes redondeados.</li>
  <li>Las teclas negras se crean agregando la clase black--key a los elementos key.</li>
  <li><b>La clase black--key</b> tiene un pseudoelemento ::after que se utiliza para crear la parte negra de la tecla.</li>
  <li><b>El pseudoelemento ::after</b> tiene un fondo negro, un ancho de 32 píxeles, un alto de 100 píxeles y está desplazado 18 píxeles a la izquierda del elemento key.</li>
  <li>El logotipo de freeCodeCamp se crea agregando un elemento img con la clase logo al elemento piano.</li>
  <li><b>El elemento logo</b> tiene un ancho de 200 píxeles y está posicionado en la esquina superior izquierda del elemento piano.</li>
</ul>


<h3>Media queries</h3>

<ol>
  <li><b>El código CSS</b> incluye dos media queries para ajustar el tamaño del piano y las teclas en dispositivos móviles y tabletas.</li>
  <li><b>La primera media query</b> se activa cuando el ancho de la ventana es de 768 píxeles o menos. Esta media query reduce el ancho del piano a 358 píxeles y el ancho de las teclas a 318 píxeles. También reduce el ancho del logotipo de freeCodeCamp a 150 píxeles.</li>
  <li><b>La segunda media query</b> se activa cuando el ancho de la ventana es de entre 769 píxeles y 1199 píxeles. Esta media query reduce el ancho del piano a 675 píxeles y el ancho de las teclas a 633 píxeles.</li>
</ol>


<h3>Conclusión</h3>

Este código crea un piano simple con 25 teclas que se puede utilizar para reproducir música. El piano tiene un diseño responsivo que se ajusta al tamaño de la ventana del dispositivo.

<footer>
  <p>
    Gracias por visitar mi sitio web. Si quieres saber más sobre mí o mi trabajo, puedes encontrarme en las siguientes redes sociales:
  </p>
  <ul>
    <li><a href="https://www.twitter.com/jerangel1">Twitter</a></li>
    <li><a href="https://www.linkedin.com/in/jerangel1/">LinkedIn</a></li>
    <li><a href="https://www.github.com/jerangel1">GitHub</a></li>
  </ul>
  <p>
    También puedes contactarme por correo electrónico a <a href="mailto:jerangel1691@gmail.com">jerangel1691@gmail.com</a>.
  </p>
</footer>

#   P i a n o 
 
 