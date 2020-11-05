+++
date = "2017-05-17T13:03:58-04:00"
title = "Pedido"
url = "/pedido"
+++

## Rellena el siguiente formulario y haz tu pedido ya!

Dejanos tu comentarios y preguntas y asi podemos ofrecerte lo mejor de nuestra cocina.
Los pedidos

<form action="https://formspree.io/f/mgepyddb" method="POST">
  <input type="text" placeholder="Tu nombre" required name="name">
  <input type="email" placeholder="Tu email" required name="_replyto">
  <input type="tel" placeholder="Tu teléfono" required name="_telnum">
  Recogida en tienda
  <input type="radio" id="si" name="recogida-en-tienda" value="si">
  Enviamelo a casa
  <input type="radio" id="no" name="recogida-en-tienda" value="no">
  Direccion
  <input type="text" name="domicilio" placeholder="Solo si has pedido a domicilio">
  <label for="plato-de-dia">Plato del dia</label>
  <input type="number" id="plato-de-dia" name="plato-del-dia" placeholder=0 min="0" max="100">
  <label for="tortilla">Tortilla</label>
  <input type="number" id="tortilla" name="tortilla" placeholder=0 min="0" max="100">
  <label for="vermut">Vermut (botella)</label>
  <input type="number" id="vermut" name="vermut" placeholder=0 min="0" max="100">
  <label for="albondigas">Albondigas (ración)</label>
  <input type="number" id="albondigas" name="albondigas" placeholder=0 min="0" max="100">
  <input type="submit" value="Enviar">
</form>

<script type="text/javascript">
  x = document.querySelectorAll('input[type="number"]');
  for (i = 0; i < x.length; i++) {
    console.log(i.value);
  }
</script>
