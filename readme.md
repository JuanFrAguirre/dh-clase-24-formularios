# Ejercitacion Formularios JavaScript Front End

## Parte 1

- Instalar las dependencias del proyecto y levantar el servidor con el comando `npm run dev`.

- Conectar la vista `contacto.ejs` con un archivo que deberemos crear para tal fin en la carpeta `public/js`.

- Crear un formulario simple que cuente con los siguientes campos:

  - **Nombre Completo** - input
  - **Correo electronico** - input
  - **Nombre de usuario** - input
  - **Contraseña** - input
  - **Repetir contraseña** - input
  - **Edad** - input
  - **Telefono** - input
  - **Genero** - radio button
  - **Suscribirme al Newsletter** - checkbox
  - **Enviar** - boton

- Lograr que al ingresar a la vista se haga foco automaticamente en el campo **Nombre Completo**.

- Prevenir que el formulario se envie y recargue la pagina.

- Una vez se haga click en el boton **Enviar**, se debera dispara una alerta de confirmacion que muestre al usuario los datos y confirme que sean correctos. De ser incorrectos, simplemente se cerrara la alerta. En caso de que este todo correcto, se debera imprimir por consola un Objeto Literal con todos los datos del usuario.

---

## Parte 2

- Impedir el envio del formulario si existen campos vacios, exceptuando el **checkbox**, **Edad** y **Telefono**.

- Agregar un campo de error para cada Input, que llenaremos dinamicamente segun los criterios que veremos a continuacion. Estos campos deberan permanecer ocultos (`display: none;`, por ejemplo) hasta que se valide que ocurra algun error, en cuyo caso se debera mostrar el mensaje de error de color rojo.

- Las validaciones seran:

  - Los campos obligatorios no pueden estar vacios
  - **Nombre completo** no puede tener menos de 6 caracteres
  - **Nombre completo** solo debe contener letras
  - **Nombre de usuario** debe tener como minimo 6 caracteres y no mas de 12
  - **Contraseña** debe tener como minimo 4 caracteres y no mas de 10
  - **Contraseña** y repetir contraseña deben ser iguales
  - **Telefono** debe tener como maximo 20 caracteres

- Si todo es exitoso, reemplazar la impresion por consola por un alerta de exito en el registro.
