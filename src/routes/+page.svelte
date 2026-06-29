
<div class="header">
  <a href="/.#presentacion">Presentación</a>
  <a href="/.#tecnologias">Tecnologías</a>
  <a href="/.#desarrollo">Desarrollo</a>
  <a href="/.#conclusion">Conclusión</a>
</div>
<div class="small-header">
  <img src="https://www.pngall.com/wp-content/uploads/2/Bridge-PNG-Pic-thumb.webp" alt="burger">
</div>
<body>
   <h1 class="objetivos">Objetivos</h1>
  <div class="card-container">
    <div class="card">
      <img src="https://t4.ftcdn.net/jpg/02/69/66/55/240_F_269665555_EUTbghVSidprZtdsV94mhuq4vObgkXGo.jpg" alt="">
    </div>
    <div class="card">
      <h1>Presentar Información Concisa que represente los valores de la compañia</h1>
    </div>
    <div class="card">
      <img src="https://t3.ftcdn.net/jpg/02/76/39/78/240_F_276397869_NKtR9outqsU1cqZd6x1gK4KaOXrWXPPl.jpg" alt="">
    </div>
    <div class="card">
      <h1>Proteger la privacidad de los trabajadores</h1>
    </div>
    <div class="card">
      <img src="https://as2.ftcdn.net/v2/jpg/00/92/93/97/1000_F_92939777_um7dW1zILDZL0ukcbt6exKK2FUWdA1av.jpg" alt="">
    </div>
    <div class="card">
      <h1>Demostrar la experiencia y capacidades de la compañía</h1>
    </div>
    <div class="card">
      <img src="https://as2.ftcdn.net/v2/jpg/03/15/86/07/1000_F_315860783_Mcb0mvumRIxKMAeFFfNqoB9Td333I9qU.jpg" alt="">
    </div>
    <div class="card">
      <h1>Ofrecer información de contacto para los clientes interesados</h1>
    </div>
  </div>
  <div class="presentacion" id="presentacion">
    <h1>Presentación</h1>
    <p>El objetivo principal es desarrollar una página web profesional, que refleje adecuadamente el trabajo realizado por la
    compañía, así como los valores y objetivos profesionales de la misma.</p>

    <p>La página debera contener el Nombre de la compañía y una presentación general, seguida de un catalogo de proyectos
    realizados, también deberá de representar el curriculum del personal de alto nivel teniendo muy en prioridad el
    preservar la privacidad del personal así como prevenir convertir a los involucrados en objetivo de ataques maliciosos,
    como recomendación personal del desarrollador sería omitir esta sección o disminuir la información lo mas posible
    para evitar exponer al personal.</p>

    <p>También debe de disponer de una sección de contacto con información reelevante para contactar al personal adecuado para
    inquisiciones de trabajo a clientes interesados. Con la libertad de que el cliente añada las secciones que considere
    necesarias para la exposición de su compañía.</p>
  </div>
  <div class="tecnologias" id="tecnologias">
    <h1>Tecnologías</h1>
    <p>
      Por el lado Técnico de desarrollo se tiene en consideración y se recomienda mantener una pagina web de caracter estático,
      esto nos permite aligerar costos a la hora de hostear la pagina para el acceso global, así como reducir al minimo los
      riesgos de ciberseguridad. Tocando el tema de la ciberseguridad, como antes se ha mencionado se recomienda mantener al
      minimo la exposición de información de contacto directo con personal.
    </p>  

    <img class="svelte_logo" src="https://images.seeklogo.com/logo-png/36/1/svelte-logo-png_seeklogo-363282.png" alt="logo">
    <p>
      Despues de deliberar en las mejores opciones de desarrollo se ha concluido en hacer el desarrollo usando un framework
      de nombre "SvelteKit", esté framework ofrece la mejor experiencia de desarrollo con HTML, CSS y Javascript para el
      desarrollo de aplicaciónes web y también ofrece compatibilidad directa y bien documentada con "Cloudflare Pages"; Lo que
      nos lleva a hablar de la propuesta para el hosting una vez creda la pagina web, se tomó la desición de usar "Cloudflare Pages"
      ya que ofrece lo que consideramos el mejor servicio a un precio adecuado para el producto a realizar, a fecha de 24 de junio
      de 2026 el plan profesional que ofrece "Cloudflare Pages", tiene un precio de 25 dólares que a esta misma fecha equivale
      a 441 pesos mexicanos, este plan ofrece el hosteo de la pagina, con 5,000 compilaciones al més, peticiones estáticas ilimitadas y
      ancho de banda ilimitado, así como todo el mantenimiento de los servidores y la seguridad implementada por la misma compañía
      para proteger en contra de ataques DDos y soporte a los estandares mas modernos de HTTP/3.
    </p>  
    <img class="cloudflare_logo" src="https://1000marcas.net/wp-content/uploads/2021/05/Cloudflare-logo.png" alt="cloudflare_logo">
    <p>
      Las otras opciones consideradas fueron Vercel que ofrece un ecosistema mas avanzado y complejo de desarrollo con capacidades
      mucho mayores que en este caso se consideran innecesarias para la escala del proyecto que se va a realizar y a un costo
      mayor con posibles repercusiones mayores en caso de ataques de negación de servicio o en caso de muchas conecciones simultaneas
      a la pagina, se considero que es un riesgo innecesario y el único sacrificio que se hace es el diseño de una pagina web
      mucho mas simple que no posee bases de datos y no ejecuta codigo en servidor.
    </p>  

    <p>
      Otra opción de hosteo alternativa fue Github Pages, que es algo utilizado bastante en el desarrollo de aplicaciónes, de hecho
      github se va a usar principalmente como herramienta de versionaje de codigo para en caso de algún problema con la última version
      de desarrollo se pueda volver sin problemas a una versión anterior, sin embargo github pages no se recomienda ser utilizado en la
      etapa de producción ya que no ofrece los serviciós de ciberseguridad que se consideran necesarios para mantener protegida la información
      de la empresa.
    </p>
  </div>
  <div class="desarrollo" id="desarrollo">
    <h1>Desarrollo</h1>
    <p>
      Se contemplo un tiempo de desarrollo para este proyecto de 30 días, en donde la estructura de desarrollo será dividida en 4 fases.
    </p>
    <div class="fases">
      <div class="fase">
        <h2>Fase 1 (Descubrimiento y Recopilación)</h2>
        <p>
          Ésta fase se caracteriza por la colecta de información y las decisiones de diseño importantes, en esta fase no se realizará ningúna
          codificación ya que lo que se espera es crear una estructura solida sobre la cual trabajar un plan de desarrollo para las siguientes
          fases de trabajo, en esta fase se espera la cooperación de el personal pertinente para conseguir toda la información reelevante para la
          compañía que se quiere exponer a los posibles clientes
        </p>
      </div>
      <div class="fase">
        <h2>Fase 2 (Codificación Inicial y comprobación de visión)</h2>
        <p>
          En la fase 2 del desarrollo se comienza la codificación en HTML y CSS de la pagina web, en esta fase se puede experimentar un poco en forma
          presentación y diseño con el objetivo de al finalizar esta fase se tenga un decisión final sobre todos estos aspectos, durante esta fase
          se seguirá en contacto constante con los encargados del proyecto denuevo con el objetivo de tener una estructura solida del proyecto. 
        </p>
      </div>
      <div class="fase">
        <h2>Fase 3 (Desarrollo Principal)</h2>
        <p>
          En la Fase principal de desarrolo ya se tiene una estructura final del proyecto y no se espera realizar cambios estructurales a la aplicación web
          cualquier cambio que requiera reconstruir codigo o modificarlo significará un retraso en la fecha final de entrega, durante esta fase se dedicará
          completamente al desarrollo con la información conseguida en previas fases y el objetivo es finalizar el proyecto completo para el final de la fase.
        </p>
      </div>
      <div class="fase">
        <h2>Fase 4 (Publicación y correción de errores)</h2>
        <p>
          En la Última fase se tiene ya el minimo aceptable para la publicación de la página por lo que se procede a la publicación en la plataforma establecida
          con el objetivo de observar el funcionamiento y corregir cualquier imprevisto que pudiera ocurrir por compatibilidad con la plataforma de hosting o por
          errores en el codigo durante está semana se haran pruebas de funcionalidad, que la aplicación sea "responsiva" a todos los dispositivos y que ofresca lo
          previamente establecido a los visitantes.
        </p>
      </div>
    </div>
  </div>
  <div class="conclusion" id="conclusion">
    <h1>Conclusión</h1>
    <p>
      Una vez terminado el proyecto se espera que no se tenga problemas en la visibilidad de la aplicación y que el funcionamiento sea constante y estable en cualquier
      situación, sin embargo imprevistos existen en cualquier industria por lo que se mantendra una supervisión constante y también dependiendo en las necesidades de la
      compañía que se pueda modificar y mejorar con el tiempo la pagina para cumplir con las necesidades que pudieran aparecer en el futuro.
    </p>
    <p>
      Se recomienda sin embargo que esta página permanezca como una aplicación estática sin complejidad de funcionamiento ya que desde un inicio se desarrollo con la simplicidad
      como objetivo, por lo que cualquier funcionalidad con ejecución de codigo en servidor implicaría una reestructuración completa, en tal caso se recomendaría un desarrollo
      paralelo de otra aplicación que pueda cumplir con estos requerimientos.
    </p>
    <p>
      Cuando se habla de funcionalidad añadida se habla especificamente de contenido dinámico en la pagina, creación de usuarios, sistemas de "newsletter", manejo de personal o inventario,
      entre otros.
    </p>
  </div> 
</body>

<div class="agradecimiento">
  <h2>Adolfo A. B.</h2>
  <p>+52 5554178404</p><p>adolfoab@gmail.com</p>
  <h3>Muchas Gracias por su Atención</h3>
</div>

<style>
  body{
    margin: 0;
    padding: 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #f4f3ee;
  }

  @media (min-width: 1800px) {
    body {
      margin: auto;
      width: 70%;
    }
  }

  .objetivos {
    padding: 0;
    margin: 20px 0 0 0;
    text-align: center;
    width: 100%;
  }

  .header{
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    background-color: #e0afa0;
    height: 100px;
    width: 100%;
    font-size: 2rem;
    box-shadow: 3px 3px gray;
  }

  .header a{
    text-decoration: none;
    color: black;
  }

  .small-header {
    display: none;
    img {
      height: 60px;
      width: 60px;
    }
  }

  @media (max-width: 800px) {
    .small-header {
      display: flex;
      justify-content: center;
      align-items: center;
      background-color: lightgray;
      width: 100%;
      height: 70px;
    }

    .header {
      display: none;
    }
  }

  .card-container {
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    align-items: center;
    overflow-x: auto;
    height: 30vh;
    width: 100%;
    background-color: #463f3a;
    scrollbar-width: thin;
  }

  .card {
    margin: 0 10px 0 10px;
    height: 90%;
    width: 500px;
    min-width: 500px;
    border: 1px solid black;
    border-radius: 5px;
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #8a817c;
    box-shadow: 3px 3px black;

    h1 {
      width: 80%;
      color: white;
    }

    img {
      width: 100%;
      height: 100%;
      border-radius: 5px;
    }
  }

  @media (max-width: 800px) {
    .card{
      width: 200px;
      min-width: 200px;

      h1 {
        font-size: 1rem;
      }
    }
  }

  .presentacion {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }

  .presentacion h1{
    font-size: 2rem;
  }

  .presentacion p{
    font-size: 1.25rem;
  }

  .tecnologias {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }

  .tecnologias h1 {
    font-size: 2rem;
  }

  .tecnologias p{
    font-size: 1.25rem;
  }

  .desarrollo {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }

  .desarrollo h1 {
    font-size: 2rem;
  }

  .desarrollo p{
    font-size: 1.25rem;
  }

  .fases {
    display: grid;
    grid-template-columns: 50% 50%;
    grid-template-rows: 50% 50%;
  }

  @media (max-width: 800px) {
    .fases {
      display:block;
    }
  }

  .fase {
    margin: 10px;
    padding: 10px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    border: 1px solid black;
    box-shadow: 3px 3px gray;
    background-color: #bcb8b1;
  }

  .conclusion {
    display: flex;
    flex-direction: column;
    justify-content: space-evenly;
    align-items: center;
  }

  .conclusion h1 {
    font-size: 2rem;
  }

  .conclusion p{
    font-size: 1.25rem;
  }
  .svelte_logo {
    height: 30vh;
  }

  @media (max-width: 800px) {
    .cloudflare_logo{
      width: 100%;
    }
  }
  .cloudflare_logo{
    height: 30vh;
  }

  .agradecimiento {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 30vh;
  }
</style>
