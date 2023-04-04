# Entrega Parcial I

[![Bootstrap][bootstrap.com]][bootstrap-url]

Modificamos todo el proyecto para que sea reponsivo ayudándonos del sistema de `Bootstrap`.

An in-depth paragraph about your project and overview of use.

Continuamos con el desarrollo de la red social añadiendo los ejercicios incrementales hechos hasta la fecha de entrega.

## Requerimientos técnicos

![JavaScritp badge](https://badges.aleen42.com/src/javascript.svg)

### Funciones JavaScript

> Algunos ejemplos

Función con `callback` para eliminar una supuesta cuenta:

```
function deleteAccount(callback) {
  users.shift();
  // Después se redirige a la página principal
  callback();
}
```

### APIs

- ?
- ?

### DOM

> Algunos ejemplos

Manipulación del contenido de `userNameError` si el usuario introduce un nombre de usuario de menos de 4 caracteres:

```
function isUserNameValid() {
  userNameError.textContent = "";
  let isValid = true;

  if (inputUserName.value.length < 4) {
    userNameError.textContent =
      "Tu nombre de usuario debe tener al menos 4 caracteres.";
    isValid = false;
  }

  return isValid;
}
```

## ?

Los dos que quedamos

- Alberto González [@albegosu](https://github.com/albegosu)
- Alejandro Pedrero [@alejandropedrero](https://github.com/alejandropedrero)

## Historial

- Parcial 1
  - HTML
  - CSS
  - Bootstrap
- Parcial 2
  - JavaScript
  - DOM
  - APIs

## Autores

Alberto González - [@albegosu](https://github.com/albegosu)  
Alejandro Pedrero - [@alejandropedrero](https://github.com/alejandropedrero)

[bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[bootstrap-url]: https://getbootstrap.com
[javascript]: https://badges.aleen42.com/src/javascript.svg
[javascript-url]: https://developer.mozilla.org/es/docs/Web/JavaScript
