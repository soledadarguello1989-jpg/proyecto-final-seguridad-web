## Error detectado en la versión v1.3

Durante la revisión del sistema se detectó que la aplicación permitía registrar contraseñas débiles como:

- 123456
- admin
- password

Este error representa un riesgo para la seguridad, porque facilita accesos no autorizados al sistema y puede permitir que un atacante adivine credenciales fácilmente.
## Acción correctiva aplicada

Para corregir el error, se establece que el sistema debe rechazar contraseñas débiles y aplicar reglas mínimas de seguridad.

Una contraseña robusta debe cumplir con lo siguiente:

- Tener mínimo 8 caracteres.
- Incluir al menos una letra mayúscula.
- Incluir al menos una letra minúscula.
- Incluir al menos un número.
- Incluir al menos un carácter especial.
- No usar datos personales como nombre, cédula o fecha de nacimiento.
- No usar contraseñas comunes como 123456, admin, password o qwerty.
- No reutilizar contraseñas anteriores.

Con esta corrección se reduce el riesgo de accesos no autorizados y se mejora la seguridad del proceso de autenticación.
