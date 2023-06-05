<template>
  <header>
    <img src="../src/assets/logo-spg.png" alt="service people group">    
  </header>
  
  <main>
    <section>
      <h2>Bienvenidos a nuestro sitio web</h2>
      <p>Próximamente estaremos lanzando nuestro nuevo sitio web. ¡Mantente atento para disfrutar de una experiencia increíble!</p>
      <p>En nuestra página principal podrás encontrar información sobre nuestros productos/servicios, nuestro equipo, y cómo contactarnos.</p>
    </section>
    
    <section>
      <h2>Novedades y Actualizaciones</h2>
      <p>Mantente al tanto de las últimas novedades y actualizaciones sobre nuestro lanzamiento. Síguenos en las redes sociales como: Service People Group</p>
    </section>
  </main>
  
  <footer>
    <p>&copy; 2023 Service People Group. Todos los derechos reservados.</p>
  </footer>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
/* Estilos generales */
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

h1, h2 {
  color: #333;
}

a {
  color: #007bff;
  text-decoration: none;
}

/* Estilos de encabezado */
header {
  background-color: #f8f8f8;
  padding: 20px;
}

header h1 {
  font-size: 28px;
  margin: 0;
}

nav ul {
  list-style: none;
  margin: 0;
  padding: 0;
}

nav ul li {
  display: inline;
  margin-right: 10px;
}

/* Estilos de secciones */
section {
  padding: 40px 20px;
  background-color: #fff;
  color: #333;
}

section h2 {
  font-size: 24px;
}

/* Estilos de pie de página */
footer {
  background-color: #333;
  color: #fff;
  padding: 20px;
  text-align: center;
}

/* Estilos adicionales */
.button {
  display: inline-block;
  padding: 10px 20px;
  background-color: #007bff;
  color: #fff;
  border-radius: 4px;
  transition: background-color 0.3s ease;
}

.button:hover {
  background-color: #0056b3;
}

/* Estilos para hacer que el sitio sea responsive */
@media screen and (max-width: 768px) {
  header {
    text-align: center;
  }
  
  nav ul li {
    display: block;
    margin-bottom: 10px;
  }
  
  section {
    padding: 20px;
  }
  
  footer {
    padding: 10px;
  }
}

</style>
