---
title: "Contacto"
permalink: "/contact.html"
---

<form action="https://formspree.io/{{site.email}}" method="POST">    
<p class="mb-4">Por favor envíe su mensaje a {{site.name}}. ¡Le contestaremos lo antes posible!</p>
<div class="form-group row">
<div class="col-md-6">
<input class="form-control" type="text" name="name" placeholder="Nombre*" required>
</div>
<div class="col-md-6">
<input class="form-control" type="email" name="_replyto" placeholder="
Dirección de Correo Electrónico @*" required>
</div>
</div>
<textarea rows="8" class="form-control mb-3" name="message" placeholder="
Mensaje*" required></textarea>    
<input class="btn btn-success" type="submit" value="Send">
</form>
