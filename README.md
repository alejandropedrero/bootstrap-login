# Entrega Parcial II 

Continuamos con el desarrollo de la red social añadiendo los ejercicios incrementales hechos hasta la fecha de entrega.

## Requerimientos técnicos

### Funciones JavaScript

> Algunos ejemplos

Función con `callback` para eliminar una supuesta cuenta

```
function deleteAccount(callback) {
  users.shift();
  // Después se redirige a la página principal
  callback();
}
```

### API

- ?
- ?

### DOM

> Algunos ejemplos

Manipulación del contenido de `userNameError` si el usuario introduce un nombre de usuario de menos de 4 caracteres

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

## Help

Any advise for common problems or issues.

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

## Autores

Los dos que quedamos

- Alberto González [@albegosu](https://github.com/albegosu)
- Alejandro Pedrero [@alejandropedrero](https://github.com/alejandropedrero)

## Historial

- Parcial 1
  - Various bug fixes and optimizations
  - See [commit change]() or See [release history]()
- Parcial 2
  - Bootstrap en toda la página
  - JavaScript

## License

This project is licensed under the [NAME HERE] License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.

- [awesome-readme](https://github.com/matiassingers/awesome-readme)
- [PurpleBooth](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
- [dbader](https://github.com/dbader/readme-template)
- [zenorocha](https://gist.github.com/zenorocha/4526327)
- [fvcproductions](https://gist.github.com/fvcproductions/1bfc2d4aecb01a834b46)
