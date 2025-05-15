<!-- Header HTML -->
<header class="site-header">
  <div class="header-container">
    <div class="logo">
      <img src="./logo-removebg-preview.png" alt="Logo CUDI" />
      <span>CUDI</span>
    </div>
    <nav class="navbar" id="navbar">
      <a href="#nosotros">Sobre Nosotros</a>
      <div class="dropdown">
        <a href="#">Herramientas</a>
        <ul class="submenu">
          <li><a href="./genrador.html">Generador de contraseñas</a></li>
          <li><a href="./verificador.html">Verificador de enlaces</a></li>
          <li><a href="#">Consultoría</a></li>
        </ul>
      </div>
      <a href="#test">Autoevaluación</a>
      <a href="./colabora.html">Colabora</a>
      <a href="https://mail.google.com/mail/?view=cm&fs=1&to=breolanapp@gmail.com" target="_blank">Contacto</a>
    </nav>
    <button class="menu-toggle" id="menu-toggle" aria-label="Abrir menú">☰</button>
  </div>
</header>

# 📘 Contenido del archivo Markdown

Este es un ejemplo de cómo puedes reutilizar el mismo encabezado y pie de página de tu web en un archivo `.md`.

## 🛡️ Tema destacado

La seguridad digital no es solo para expertos. En CUDI promovemos el conocimiento práctico y accesible.

---

## 📎 Recursos

- [Verificador de enlaces](./verificador.html)
- [Guía de contraseñas seguras](#)
- [¿Qué es el phishing?](#)

<!-- Footer HTML -->
<footer>
  <p>&copy; 2025 CUDI - Comunidad de Usuarios para la Defensa Informática</p>
</footer>

<!-- Script para toggle del menú -->
<script>
  document.getElementById("menu-toggle").addEventListener("click", function () {
    document.getElementById("navbar").classList.toggle("show");
  });
</script>
