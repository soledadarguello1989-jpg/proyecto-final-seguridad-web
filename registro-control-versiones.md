# Registro de control de versiones del sistema de rol de pagos

| Versión | Ambiente | Cambio realizado | Responsable | Estado |
|---|---|---|---|---|
| v1.0 | Desarrollo | Creación inicial del sistema de rol de pagos | Soledad Argüello | Estable |
| v1.1 | Desarrollo | Creación login inicial | Soledad Argüello | Estable |
| v1.2 | Desarrollo | Manual de validación de contraseñas | Soledad Argüello | Estable |
| v1.3 | Certificación | Se detecta error: contraseñas débiles permitidas | Soledad Argüello | Con error |
| v1.2 | Certificación | Retorno a versión anterior estable | Soledad Argüello | Restaurada |
| v1.4 | Producción | Corrección final de validación de contraseñas | Soledad Argüello | Estable |

## Descripción del error

En la versión v1.3 se detectó que el sistema permitía registrar contraseñas débiles. Esto generaba un riesgo porque el sistema de rol de pagos contiene información sensible del personal.

## Retorno a versión anterior

Al identificar el error, se revisó el historial de GitHub y se tomó como referencia la versión anterior estable v1.2. Luego se corrigió la validación de contraseñas y se generó la versión v1.4 para producción.
