---
layout: layouts/base.njk
eleventyNavigation:
  key: Sobre
  order: 3
---
# Sobre front.es


Contacto:
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Nombre: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Tu rol: <select name="role[]" multiple>
      <option value="desarrollador">Desarrollador</option>
      <option value="maquetador">Maquetador</option>
			<option value="fullstack">Full stack</option>
			<option value="ux">UX</option>
    </select></label>
  </p>
  <p>
    <label>Mensaje: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Enviar</button>
  </p>
</form>
