<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>María Fernanda Apaza Meza</title>
  <style>
    :root {
        --background-light: white;
        --text-light: #333;
        --background-dark: #FFE4B3;
        --text-dark: white
    }
    
    body {
      font-family: Arial, sans-serif;
      background-color: #FFE4B3;
      margin: 0;
      padding: 0;
      color: #FFE4B3;
      TRANSITION: 0.3s;
    }
    
    header, footer {
      text-align: center;
      background-color: #FFB51F;
      color: white;
    }
    
    nav {
      background-color: #FFB51F;
      padding: 1rem;
      text-align: center;
    }
    
    nav a {
      color: white;
      text-decoration: none;
      margin-right: 0;
    }
    
  a {
    color:#3498db;
    text-decoration:none;
  }
  
    section {
        padding: 2rem;
        margin: 1rem auto;
        max-width: 800px;
        background: white;
        border-radius: 8px;
        box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
    }
    
    .section-title {
      color: #fe470a;
      font-weight: bold;
      font-size: 1.5em;
      margin-bottom: 10px;
    }
    
    .divider {
      border-top: 1px solid #ccc;
      margin: 10px 0;
    }
    
    .section-text {
      color: black;
      font-size: 0.95em;
    }
    
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
      gap: 20px;
    }
    
    .card {
      background-color: #f0f0f0;
      padding: 15px;
      border-radius: 10px;
    }
    
    .card-title {
      color: #fe470a;
      font-weight: bold;
      font-size: 1.2em;
    }
    .sobremi-container {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
  align-items: center;
}

.sobremi-img img {
  width: 100%;
  maz-width: 220px;
  height: auto;
  border-radius: 10px;
  object-fit: cover;
  display: block;
  margin: 0 auto;
}

@media (min-width: 768px) {
  .sobremi-container {
    grid-template-columns: 165px 1fr;
    align-items: flex-start;
  }

  .sobremi-img img {
    max-width: 165px;
    height: auto;
    margin: 0;
  }

  .sobremi-img {
    margin-right: 0;
  }

  .sobremi-text {
    flex: 1;
  }
}
  </style>
</head>
<body>
  <header>
    <h1>María Fernanda Apaza Meza</h1>
    <h2>Estudiante de Administración de Negocios en la UCSP</h2>
  </header>
  <nav>
    <a href="#sobremi">Sobre mí</a>
    <a href="#cursos-universitarios">Cursos Universitarios</a>
    <a href="#cursos-adicionales">Voluntariados y Conferencias</a>
    <a href="#idiomas">Idiomas</a>
    <a href="#amigos">Amigos y Compañeros</a>
    <a href="#contacto">Contacto</a>
  </nav>
  
  <section id="sobremi">
    <div class="section-title">Sobre mí</div>
    <div class="divider"></div>
    <div class="sobremi-container">
      <div class="sobremi-img">
      <img src="https://raw.githubusercontent.com/MariaFernandaApazaMeza/Pagina-web/main/Foto%20de%20Maria%20Fernanda%20Apaza%20Meza%20con%20el%20Doctor%20Alonso%20Quintanilla%20P%C3%A9rez-Wicht.jpg" alt="Foto de María Fernanda Apaza Meza" />
    </div>
    <div class="section-text sobremi-text">
      Hola soy Mafer, una estudiante de la carrera de Administración de Negocios en la 
      <a href="https://ucsp.edu.pe/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      Universidad Católica San Pablo
      </a>. Me interesa comprender cómo las organizaciones pueden crecer de forma sostenible a través de estrategias bien estructuradas y una gestión eficiente. Durante mi formación, he fortalecido competencias clave como el trabajo colaborativo, la comunicación efectiva y la toma de decisiones. Tengo un especial interés en áreas como el marketing, el análisis financiero y el liderazgo, ya que considero que son fundamentales para generar impacto en el entorno empresarial actual.
      </div>
    </div>
  </section>
  <section id="cursos-universitarios">
    <div class="section-title">Cursos Universitarios</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Economía General</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/karlolam?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Karlo Alfonso Lam Obregón</a>
      </div>
      <div class="card"><div class="card-title">Fundamentos de la Administración</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/jackelinecv?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Jackeline Castillo Vera</a>
      </div>
      <div class="card"><div class="card-title">Pensamiento Crítico</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/ana-elizabeth-g%C3%B3mez-burns-4502263b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Ana Elizabeth Gómez Burns</a>
      </div>
      <div class="card"><div class="card-title">Derecho Empresarial</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/katherinelazogonzales?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Katherine Lazo Gonzales</a><p/>
      </div>
      <div class="card"><div class="card-title">Fundamentos del Marketing</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/sofiaestremadoyro?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Sofía Estremadoyro Bejarano</a><p/>
      </div>
      <div class="card"><div class="card-title">Matemática Financiera</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/gerardorea%C3%B1o?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Gerardo Velarde Reaño</a><p/>
      </div>
      <div class="card"><div class="card-title">Análisis Financiero</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/lelia-rubina-27939889?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Lelia Maria Rubina Guillen</a><p/>
      </div>
      <div class="card"><div class="card-title">Introducción a las Ciencias de la Computación</div>
      <p class="section-text">Docente: </p><a href="https://www.linkedin.com/in/ecuadrosv?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">Ernesto Cuadros Vargas</a><p/>
      </div>
    </div>
  </section>
  
  <section id="Voluntariados y Conferencias">
    <div class="section-title">Voluntariados y Conferencias</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Ruta del progreso</div>
      <p class="section-text">
      Participé como voluntaria en La Ruta del Progreso, una feria itinerante realizada en la Plaza de Yanahuara, Arequipa, que promueve la educación financiera a través de talleres, charlas y dinámicas para todas las edades. El evento contó con la participación de 
      <a href="https://www.viabcp.com/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      BCP
      </a>, <a href="https://www.mibanco.com.pe/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      MI BANCO
      </a>, <a href="https://www.prima.com.pe/public-zone/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      PRIMA
      </a> y <a href="https://www.pacifico.com.pe/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      PACÍFICO SEGUROS
      </a>. Esta experiencia reforzó mi compromiso con la inclusión financiera y el desarrollo comunitario.
      </p>
      </div>
      <div class="card"><div class="card-title">PMI</div>
      <p class="section-text">
      Mi participación en el PMI (Project Management Institute) marcó el inicio de un valioso recorrido profesional. Allí conocí a 
      <a href="https://www.linkedin.com/in/eduardolanao/" target="blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      Eduardo Lanao,
      </a>con quien profundicé en temas de minería sostenible, y a <a href="https://www.linkedin.com/in/eddy-morris-ph-d-64a73940/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      Eddy Morris
      </a>, ( Decano de la Facultad de Ingeniería <a href="https://www.esan.edu.pe/" target="_blank" style="color:#000; font-weight:bold; text-decoration:underline;">
      ESAN
      </a>
       ) referente en transformación digital y educación ejecutiva. Este evento fue clave para ampliar mi visión sobre el desarrollo empresarial.
      </p>
      </div>
    </div>
  </section>
        
  <section id="idiomas">
    <div class="section-title">Idiomas</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Inglés</div>
        <p class="section-text">El dominio del inglés representa una herramienta fundamental en el ámbito académico y profesional, ya que permite acceder a información actualizada, literatura especializada y oportunidades internacionales. Es un idioma clave para los negocios y la gestión empresarial.</p><a href="https://cultural.edu.pe/arequipa/">Centro Cultural Norteamericano</a>
        <p/>
      </div>
      <div class="card"><div class="card-title">Francés</div>
        <p class="section-text">El conocimiento del francés amplía el alcance profesional al abrir puertas en mercados internacionales, especialmente en países francófonos. Además, fortalece el perfil académico y cultural, lo que resulta valioso en contextos empresariales globalizados.</p><a href="https://afarequipa.org.pe/">Alianza Francesa</a>
        <p/>
      </div>
    </div>
  </section>
  
  <section id="amigos">
    <div class="section-title">Amigos y Compañeros</div>
    <div class="divider"></div>
    <div class="grid">
      <div class="card"><div class="card-title">Alvaro Apaza</div>
     <a href="https://alvaroenriqueapazaluque.github.io/AlvaroApazaLuque.github.io/">Alvaro Apaza Luque</a><p/>
      </div>
      <div class="card"><div class="card-title">Valentina Bedregal</div>
      <a href="https://www.linkedin.com/in/valentina-bedregal-151770340?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a><p/>
      <a href="https://graziavalentina.github.io/Grazia-Valentina-Bedregal-Ochoa/">Gracia Valentina Bedregal Ochoa</a><p/>
      </div>
      <div class="card"><div class="card-title">Rodrigo Bohórquez</div>
     <a href="https://www.instagram.com/rodrigo_bh27?igsh=MTdwanpncjlrNXp4OA==">Rodrigo Bohórquez</a><p/>
      </div>
      <div class="card"><div class="card-title">Thirza Cansaya</div>
      <a href="https://www.linkedin.com/in/thirza-alexka-cansaya-escobedo-588112292/">Linkedln</a>
<p/>
      <a href="https://thirzaalexkacansayaescobedo.github.io/ThirzaCansaya/">Thirza Alexka Cansaya Escobedo</a><p/>
      </div>
      <div class="card"><div class="card-title">Fabian Cayo</div>
      <a href="https://www.linkedin.com/in/fabi%C3%A1n-cayo-calcina-177709219?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a>
<p/>
      <a href="https://fabianrodrigocayocalcina.github.io/">Fabian Rodrigo Cayo Calcina</a><p/>
      </div>
      <div class="card"><div class="card-title">Piero Chahuares</div>
      <a href="https://www.linkedin.com/in/piero-mathias-chahuares-d%C3%ADaz?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a>
<p/>
      <a href="https://pierochahuares.github.io/Piero-Mathias-Chahuares-D-az/">Piero Mathias Chahuares Díaz</a><p/>
      </div>
      <div class="card"><div class="card-title">Leonardo Cruz</div>
     <a href="https://leonardocruzmamani28.github.io/">Leonardo Guillermo Cruz Mamani</a><p/>
      </div>
      <div class="card"><div class="card-title">Pedro Flores</div>
     <a href="https://pedro191102.github.io/Pedro-Fabian-Zahir-Flores-Gutierrez/">Pedro Fabián Zahir Flores Gutierrez</a><p/>
      </div>
      <div class="card"><div class="card-title">Krislet Juarez</div>
      <a href="https://www.linkedin.com/in/krislet-yahaira-juarez-arce-a97570357?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a>
<p/>
      <a href="https://krisletyahairajuarezarce.github.io/Krislet-Yahaira-Juarez-Arce/">Krislet Yahaira Juarez Arce</a><p/>
      </div>
      <div class="card"><div class="card-title">Mariano Mendoza</div>
      <a href="https://www.linkedin.com/in/mariano-mendoza-pinto-153a52249?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a><p/>
      <a href="https://mmenddoza.github.io/Mariano-Andrei-Mendoza-Pinto/">Mariano Andrei Mendoza Pinto</a><p/>
      </div>
      <div class="card"><div class="card-title">Maria Jose Montoya</div>
     <a href="https://maria-035.github.io/maria.montoya.cardenas-/">Maria Jose Montoya Cardenas</a><p/>
      </div>
      <div class="card"><div class="card-title">Sergio Palomino</div>
      <a href="https://www.linkedin.com/in/palomino-rosado-sergio-gonzalo-a64996356?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a><p/>
      <a href="https://sergipalomino.github.io/Perfil.Sergio.PR/">Sergio Gonzalo Palomino Rosado</a><p/>
      </div>
      <div class="card"><div class="card-title">Fabiola Terán</div>
      <a href="https://www.linkedin.com/in/alexandra-escobedo-07a227211/">Linkedln</a>
<p/>
      <a href="https://alexandrafabiola.github.io/alexandra-escobedo/">Alexandra Fabiola Escobedo Terán</a><p/>
      </div>
      <div class="card"><div class="card-title">Thalia Torres</div>
     <a href="https://essie-torres.github.io/mi-sitio-web/">Thalia Esther Torres Banda</a><p/>
      </div>
      <div class="card"><div class="card-title">Vanessa Yesán</div>
      <a href="https://www.linkedin.com/in/vanessa-alexandra-yesan-valdivia-8810a5334?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app">Linkedln</a>
<p/>
     <a href="https://vanessa-alexandra-yesan-valdivia.github.io/">Vanessa Alexandra Yesan Valdivia</a><p/>
      </div>
    </div>
    
  </section>
  <section id="contacto">
    <div class="section-title">Contacto</div>
    <div class="divider"></div>
    <p class="section-text">📧 Gmail</p>
    <a href="maria.apaza.meza@ucsp.edu.pe">maria.apaza.meza@ucsp.edu.pe</a><p/>
    <p class="section-text">Linkedln</p>
    <a href="https://www.linkedin.com/in/mar%C3%ADa-fernanda-apaza-meza-3926aa29b?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app">🔹María Fernanda Apaza Meza</a>
    <p/>
  </section>
</body>
</html>
